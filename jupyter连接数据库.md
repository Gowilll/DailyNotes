```python
import pandas as pd
from sqlalchemy import create_engine

# 1. 配置数据库连接参数（请根据实际情况修改）
db_user = "root"
db_password = "你的密码"
db_host = "localhost"
db_port = "3306"
db_name = "test_database"

# 2. 创建数据库连接引擎
engine = create_engine(
    f"mysql+pymysql://{db_user}:{db_password}@{db_host}:{db_port}/{db_name}?charset=utf8mb4"
)

# 3. 用 pandas 读取数据表（如 gdp_data）
sql = "SELECT * FROM gdp_data LIMIT 10"
df = pd.read_sql(sql, con=engine)

# 4. 展示数据
df

```

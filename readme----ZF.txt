# 推荐先安装pipenv
pip install pipenv -i https://mirrors.aliyun.com/pypi/simple/

# 先进入到项目文件下
cd /项目目录/MallAPI

# 安装pipenv python版本3.7+
pipenv install --python 3.8 # 注意 --python空格3.8

# 安装完后激活环境
pipenv shell

# 安装依赖
pip install -r requirements.text -i https://mirrors.aliyun.com/pypi/simple/

启动
cd /项目目录/MallAPI

# 在main.py文件同级目录下 执行
uvicorn main:app --host=127.0.0.1 --port=8010 --reload
当然也可以直接执行

python main.py
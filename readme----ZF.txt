# �Ƽ��Ȱ�װpipenv
pip install pipenv -i https://mirrors.aliyun.com/pypi/simple/

# �Ƚ��뵽��Ŀ�ļ���
cd /��ĿĿ¼/MallAPI

# ��װpipenv python�汾3.7+
pipenv install --python 3.8 # ע�� --python�ո�3.8

# ��װ��󼤻��
pipenv shell

# ��װ����
pip install -r requirements.text -i https://mirrors.aliyun.com/pypi/simple/

����
cd /��ĿĿ¼/MallAPI

# ��main.py�ļ�ͬ��Ŀ¼�� ִ��
uvicorn main:app --host=127.0.0.1 --port=8010 --reload
��ȻҲ����ֱ��ִ��

python main.py
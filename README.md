Los requirements tambien fueron sacados de mi repo: https://github.com/fedriki060/Taller-AWS-EIA-SO

**Comandos usados:
- ssh -i Final-OS.pem ubuntu@13.59.32.85

- sudo apt update
- sudo apt install python3-pip python3-venv git -y

- python3 -m venv venv
- source venv/bin/activate

- pip install -r requirements.txt

- sudo apt install mysql-server -y
- sudo systemctl start mysql
- sudo systemctl enable mysql

- uvicorn main:app --host 0.0.0.0 --port 8000
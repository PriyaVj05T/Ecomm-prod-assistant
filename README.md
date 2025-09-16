# commands for cmd 
pip install uv
uv --version
import shutil
print(shutil.which("uv"))
>>cd to project folder directory
eg: uv init ECOMM-PROD-ASSISTANT
>> cd ECOMM-PROD-ASSISTANT 
>> code . ( will open project in Vs code)
base directory>>
uv pip list
uv python list
uv python install cpython-3.12.3-windows-x86_64-none 
uv venv <prod-env> --python cpython-3.10.18-windows-x86_64-none 
---for activating environment just copy activate.bat path from environment folder and run eg:
 D:\data\Projects\Ecomm-prod-assistant\prod-env\Scripts\activate.bat for cmd---
uv pip install -r requirements.txt
uv add -r requirements.txt
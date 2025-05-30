# PA-vehicle-registration
Automate vehicle registration process in Pennsylvania, US

## Pre-requisites
- Python 
- XQuartz (for GUI remote access)

## How to run

1. Install and Open XQuartz to allow remote-access to the server via GUI:
```bash
open -a XQuartz
```

2. Add remote server to xhost list:
```bash
xhost +<server-url>
```

3. Connect to the server via SSH:
```bash
ssh -Y <user-name>@<server-url>
```

4. Install required packages:
```bash
pip install -r requirements.txt
```

5. Run the script:
```bash
python main.py
```
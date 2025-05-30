# PA-vehicle-registration
Automate vehicle registration process in Pennsylvania, US

## Demo Video
https://www.loom.com/share/28fd86c8b9e948bdaa98d46527edc6d2?sid=e41fdd24-f6fb-40c7-abd4-63e18df40de0

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
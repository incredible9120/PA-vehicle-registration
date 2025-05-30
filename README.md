# PA-vehicle-registration
Automate vehicle registration process in Pennsylvania, US

## Demo Video
https://www.loom.com/share/65600bd5529747d1884f0dcfb60abfa3?sid=d36e3fa3-e377-4cff-81d9-74d2edd9c92d

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
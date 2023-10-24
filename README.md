# ton-connect-bot
A simple bot written on Python to interact with TON wallets using Ton Connect protocol

## How to launch

### Redis
If you want to use permanent TON Connect storage you should [set up Redis](https://redis.io/docs/getting-started/) or any other database.


### Install dependencies:

```bash
pip install -r requirements.txt
```

### Set up `.env`:

```dotenv
TOKEN='1111:ABCD'  # your bot token here
MANIFEST_URL='https://raw.githubusercontent.com/XaBbl4/pytonconnect/main/pytonconnect-manifest.json'
```

### Run bot

```python
python3 src/main.py
```

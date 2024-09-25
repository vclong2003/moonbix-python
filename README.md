# Moonbix Python - A Python bot for Binance Moonbix game

## How to use it?

Make sure you have Python 3, pip installed.

1. Open the Binance Moonbix bot.
2. Get auth data `query_id=...` or `user=...` in the `Application` tab in DevTools. Or use your own way to get it.
3. Create the `data.txt` file and paste the auth data in it.
4. Create Python virtual environment and install the requirements:
   1. `python3 -m venv env`
   2. `source env/bin/activate` (Linux) or `.\env\Scripts\Activate.ps1` (Windows)`
   3. `pip3 install -r requirements.txt`
5. Run the bot:
   1. `python3 bot.py` (without proxy)
   2. `python3 bot-proxy.py` (with proxy)

```bash
██╗   ██╗ ██████╗██╗
██║   ██║██╔════╝██║
██║   ██║██║     ██║
╚██╗ ██╔╝██║     ██║
 ╚████╔╝ ╚██████╗███████╗
  ╚═══╝   ╚═════╝╚══════╝
```

# Chatstats SDK

## Usage

First, get token from [@chatstatbot](https://t.me/chatstatbot?start=token) 

```python
from chatstats.sync_api import SyncChatStats

chat_stats = SyncChatStats(token='<YOUR TOKEN FROM BOT>')
chat_stats.new_event(
    event_name='/start',
    user_first_name='Bogdan',
    user_last_name='Evstratenko',
    user_username='evstrat',
    user_id='56631662',
    user_language_code='ru',
    is_bot=False,
)
```


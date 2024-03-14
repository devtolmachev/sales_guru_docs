# Technologies reference

## Used libraries

For work with JSON:

- Orjson - [GitHub](https://github.com/ijl/orjson)

For Validation:

- Pydantic - [Docs](https://docs.pydantic.dev/latest/)
- Jsonschema - [Docs](https://python-jsonschema.readthedocs.io/en/stable/)
  
For http/https requests:

- Aiohttp
- requests
- fake_useragent

For parsing:

- strip-markdown (get normal text from markdown)
- beautifulsoup4
- lxml

For work with databases:

- SQLAlchemy
- Motor (for work with mongodb)
- AsyncPg (async postgresql driver which uses sqlalchemy)
- Aiosqlite

For cache:

- redis
- cachetools

For configurate project:

- EnvYaml
- Pydantic-settings
- betterconf
- bestconfig

For testing:

- Pytest
- Pytest-bdd
- Pytest-async
- pytest-xdist
- pytest-asyncio

For AI:

- openai
- g4f

For docs:

- mkdocstrings
- mkdocs-material

For serialization:

- dill

For ELK stack:

- elasticsearch
- python-logstash-async

For logging:

- loguru

For IO operations:

- aiofiles

For control memory:

- psutil

For run realy blocked tasks:

- Cellery

For view celery tasks in web:

- Flower

For work with date:

- isodate

For TELEGRAM

- telethon
- pyrogram
- aiogram
- teleredis
- telemongo
- telethonfaketls

Other:
  
- selenium (browser automations)
- playwright (browser automations)
- phonenumbers (for phone numbers)
- tqdm (for progress bar - IS DEPRECATED)
- transliterate (for revert message text)
- spintax - see [what is it](https://support.saleshandy.com/article/345-what-is-spintax-and-how-to-use-it#:~:text=Spintax%20is%20short%20for%20'Spin,(pipe)%20to%20use%20Spintax.) and [docs](https://github.com/AceLewis/spintax.git)
- undetected-chromedriver (for selenium and playwright)
- random-username
- faker (for get random data)

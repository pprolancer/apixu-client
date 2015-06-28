apixu-client
========

A python client library to call Apixu api.

Installation:
-------------------
python setup.py install


Example usage:
-------------------

```python
from apixu.client import ApixuClient, ApixuException
api_key = 'xxxxxxxxxxxx'
client = ApixuClient(api_key)
client.getCurrentWeather(q='London')
client.getForecastWeather(q='07112', days=7)
```

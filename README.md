apixu-client
========

A client for call Apixu api.

Installation:
-------------------
python setup.py install


Example usage:
-------------------
.. code-block:: python
from apixu.client import ApixuClient, ApixuException
client = ApixuClient('API_KEY')
client.getCurrentWeather(q='London')
client.getForcastWeather(q='07112', days=7)


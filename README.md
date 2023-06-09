# Iplookupapi Python Client #

iplookupapi Python Client is the official Python Wrapper around the iplookupapi [API](https://iplookupapi.com/).

## Installation

Install from pip:
````sh
pip install iplookupapi
````

Install from code:
````sh
pip install git+https://github.com/everapihq/iplookupapi-python.git
````

## Usage

All iplookupapi API requests are made using the `Client` class. This class must be initialized with your API access key string. [Where is my API access key?](https://app.iplookupapi.com/dashboard)

In your Python application, import `iplookupapi` and pass authentication information to initialize it:

````python
import iplookupapi
client = iplookupapi.Client('API_KEY')
````

### Retrieve Status

```python

print(client.status())

```

### Retrieve IP Information
[https://iplookupapi.com/docs/info](https://iplookupapi.com/docs/info)
```python

result = client.info()
# result = client.info('1.1.1.1', 'de')
print(result)

```


### Contact us
Any feedback? Please feel free to [contact our team](mailto:office@everapi.com).

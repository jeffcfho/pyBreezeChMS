PyBreezeChMS
=================

Python interface to BreezeChMS REST API http://www.breezechms.com

[![Build Status](https://travis-ci.org/alexortizrosado/pyBreezeChMS.svg?branch=master)](https://travis-ci.org/alexortizrosado/pyBreezeChMS) [![Coverage Status](https://coveralls.io/repos/alexortizrosado/pyBreezeChMS/badge.png)](https://coveralls.io/r/aortiz32/pyBreezeChMS)

## Installation

Before using pyBreezeChMS, you'll need to install the [requests](http://docs.python-requests.org/en/latest/) library:

    $ sudo pip install requests

## Getting Started

```python
from breeze import breeze

breeze_api = breeze.BreezeApi(
    breeze_url='https://your_subdomain.breezechms.com',
    api_key='YourApiKey')
```

To get a JSON of all people:

```python

people = breeze_api.get_people()
```

## License

Code released under the [Apache 2.0](https://github.com/aortiz32/pyBreezeChMS/blob/master/LICENSE) license.

# Fenikss Parse

Fenikss Parse - blazing fast HTTP request parsing library.

## Installation

`pip install fenikss-parse`

## Usage

Usage is very-very simple:

**URL parser:**

```python
from fenikss_parse import parse_url
URL = ...
result = parse_url(URL)
```

**Request parser:**

```python
from fenikss_parse import parse_request
REQUEST = ...
result = parse_request(REQUEST, '127.0.0.1:81762')
```

## Post Scriptum

Please, mention project with full name ("Fenikss Parse"), thanks.

## License

MIT.

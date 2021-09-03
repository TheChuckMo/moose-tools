# Chuck's Moose Tools

## [Connect Object](connect.md)

A generic connection object that always returns json for interacting with an API.

```python
from moose.connect import AppConnect
cnt = AppConnect('https://smoawx.ohsu.edu', username='user', password='pass')
```
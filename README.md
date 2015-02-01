Python module for the velleman k8056 relay card.

### Example
```python
from k8056 import K8056

with K8056('/dev/ttyS0') as relaycard:
    relaycard.set(1)
```
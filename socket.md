
# Socket
- [Get Hostname](#get-hostname)

<br><br>
### Get Hostname
```python
>>> import socket
>>> socket.gethostname()
'root@bisratyalew'

>>> hostname = socket.gethostname()

>>> socket.gethostbyname('localhost')
'127.0.0.1'

>>> socket.gethostbyname(hostname) ### Returns ip address
'192.168.1.3'

```

### [Back To Top](#socket)
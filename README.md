# Dareplane Pynet

This is a very small helper tool which allows for a quick TCP connection which can be used instead of `telnet` to connect to a server:port and send a messages.

## User

```bash
python pynet.py --server="localhost" --port=8080
```

Note that the `--server` and `--port` are used to overwrite the default values. If your module is running at port 8080 on localhost (usually pointing to `127.0.0.1`), you can just do `python pynet.py`.

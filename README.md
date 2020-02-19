# jy
json to yaml conversion

To build:
```
$ go build
$ cp jy yj
```

example usage:

```
$ echo '{ "a":1, "b": "xyz" } ' | jy
a: 1
b: xyz

$ echo '{ "a":1, "b": "xyz" } ' | jy | yj
{"a":1,"b":"xyz"}
```

# prettyjson

JSON pretty print for Golang.

![CI](https://github.com/singlemusic/go-prettyjson/workflows/CI/badge.svg?branch=master)

## Example

```go
v := map[string]interface{}{
    "str": "foo",
    "num": 100,
    "bool": false,
    "null": nil,
    "array": []string{"foo", "bar", "baz"},
    "map": map[string]interface{}{
        "foo": "bar",
    },
}
s, _ := prettyjson.Marshal(v)
fmt.Println(string(s))
```

![Output](http://i.imgur.com/cUFj5os.png)

## License

MIT

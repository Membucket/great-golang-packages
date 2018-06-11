# great-golang-packages
Curated list of Golang packages that (often) perform better than those found in core.

## net

- `net/http` client or server: [fasthttp](https://github.com/valyala/fasthttp)

## encoding

- for schema-based formats: [flatbuffers](https://github.com/google/flatbuffers/tree/master/go)
- `encoding/json` replacement: [gjson](https://github.com/tidwall/gjson)

## log

- [logrus](https://github.com/sirupsen/logrus) is featureful but slow, use [logxi](https://github.com/AlbinoGeek/logxi) instead

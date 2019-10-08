# serializeCookie
This snippet can be used to serialize a cookie name-value pair into a Set-Cookie header string.

```
const serializeCookie = (name, val) => `${encodeURIComponent(name)}=${encodeURIComponent(val)}`;
```

**Usage:**
```
serializeCookie('foo', 'bar'); // 'foo=bar'
```

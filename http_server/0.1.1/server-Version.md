# Version
<span class="source-link">[[Source]](src/server/request.md#L29)</span>

union of supported HTTP Versions

See: https://tools.ietf.org/html/rfc2616#section-3.1


```pony
type Version is
  ((HTTP09 val | HTTP10 val | HTTP11 val) & _Version val)
```

#### Type Alias For

* (([HTTP09](server-HTTP09.md) val | [HTTP10](server-HTTP10.md) val | [HTTP11](server-HTTP11.md) val) & _Version val)

---


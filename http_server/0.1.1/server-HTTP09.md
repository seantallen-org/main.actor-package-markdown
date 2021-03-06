# HTTP09
<span class="source-link">[[Source]](src/server/request.md#L21)</span>

HTTP/0.9


```pony
primitive val HTTP09 is
  _Version val
```

#### Implements

* _Version val

---

## Constructors

### create
<span class="source-link">[[Source]](src/server/request.md#L21)</span>


```pony
new val create()
: HTTP09 val^
```

#### Returns

* [HTTP09](server-HTTP09.md) val^

---

## Public Functions

### string
<span class="source-link">[[Source]](src/server/request.md#L25)</span>


```pony
fun box string()
: String iso^
```

#### Returns

* [String](builtin-String.md) iso^

---

### to_bytes
<span class="source-link">[[Source]](src/server/request.md#L26)</span>


```pony
fun box to_bytes()
: Array[U8 val] val
```

#### Returns

* [Array](builtin-Array.md)\[[U8](builtin-U8.md) val\] val

---

### eq
<span class="source-link">[[Source]](src/server/request.md#L27)</span>


```pony
fun box eq(
  o: ((HTTP09 val | HTTP10 val | HTTP11 val) & _Version val))
: Bool val
```
#### Parameters

*   o: (([HTTP09](server-HTTP09.md) val | [HTTP10](server-HTTP10.md) val | [HTTP11](server-HTTP11.md) val) & _Version val)

#### Returns

* [Bool](builtin-Bool.md) val

---

### ne



```pony
fun box ne(
  that: ((HTTP09 val | HTTP10 val | HTTP11 val) & _Version val))
: Bool val
```
#### Parameters

*   that: (([HTTP09](server-HTTP09.md) val | [HTTP10](server-HTTP10.md) val | [HTTP11](server-HTTP11.md) val) & _Version val)

#### Returns

* [Bool](builtin-Bool.md) val

---


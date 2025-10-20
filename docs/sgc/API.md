# Memory
Provides static methods that manipulate memory directly.

## Methods
```sgcode
public static null* Alloc(int size)
```
### Parameters
`int size`: The size of the memory block in bytes.

### Returns
`null*`: The pointer to the allocated memory.

```sgcode
public static null Copy(null* src, null* dst, int length)
```
### Parameters
`null* src`: The source block to copy from.
`null* dst`: The destination block to copy to.
`int length`: The length in bytes to copy.

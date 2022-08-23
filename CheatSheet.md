
### `set <key> <value>`
this will set the value of the key to the value and returns ok

### `get <key>`
this will return the value of the key

### `del <key>`
this will delete the key and returns ok

### `keys <pattern>`
this will return all keys matching the pattern

you can use * as a wildcard to get all keys

### `exists <key>`
this will return 1 if the key exists and 0 if it doesn't

### `incr <key>`
this will increment the value of the key by 1 and returns the new value, value must be an integer

### `decr <key>`
this will decrement the value of the key by 1 and returns the new value, value must be an integer

### `incrby <key> <value>`
this will increment the value of the key by the value and returns the new value, value must be an integer

### `decrby <key> <value>`
this will decrement the value of the key by the value and returns the new value, value must be an integer


# Get list from Redis

```php
$redis->lrange('list1', 1, 4);
```

- `$redis` - Redis object after [connection](/php-redis/how-to-connect-to-redis)
- `lrange` - returns specified elements from the list
- `list1` - name of the list to get elements of
- `1,` - index of the first element (starts with `0`, so we're starting from second element)
- `4)` - index of the last element

group: list


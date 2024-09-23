# ZREM

`ZREM` is a Redis command used to remove one or more members from a sorted set. Each member is specified by its unique value, and the corresponding entry is deleted if it exists in the sorted set. The sorted set remains sorted by score, and the command returns the number of members that were removed. If a member does not exist in the set, it is ignored without causing an error.

Learn more from the following resources:

- [@official@ZREM Documentation](https://redis.io/docs/latest/commands/zrem/)
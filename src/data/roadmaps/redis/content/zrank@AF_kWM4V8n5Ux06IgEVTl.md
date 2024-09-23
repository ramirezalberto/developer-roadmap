# ZRANK

`ZRANK` is a Redis command that returns the rank (or index) of a member in a sorted set, with the scores sorted in ascending order. The rank is zero-based, meaning the member with the lowest score has a rank of 0. If the member is not found in the sorted set, the command returns `nil`. This command is useful for determining the position of an element relative to others in the set based on its score.

Learn more from the following resources:

- [@official@ZRANK Roadmaps](https://redis.io/docs/latest/commands/zrank/)
#### Quotas {#logging-quotas}

| Type of limit | Value |
| ----- | ----- |
| Number of custom log groups per cloud | 10 |

#### Limits {#logging-limits}

| Type of limit | Value |
| ----- | ----- |
| **Adding records** |
| Maximum number of records per request | 100 |
| Maximum record size | 128 KB |
| Maximum `message` size | 64 KB |
| Maximum `json-payload` size | 64 KB |
| Maximum write speed | 10 MB/s or 1000 records per second |
| **Reading records** |
| Maximum number of requests per second | 5 |
| **Other restrictions** |
| Minimum record retention period | 1 hour |
| Maximum record retention period | 3 days |
| Maximum length of a [filter](../../logging/concepts/filter.md#how-to) | 1000 characters |
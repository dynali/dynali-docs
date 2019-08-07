myip method
===========

Returns client's IP as detected by Dynali.

# Input 

| parameter | value type | value |
|-----------|------------|-------|
| action    | string     | myip  |

## Sample

```
{"action":"myip"}
```

# Output

| attribute | value type   | value           | occurence |
|-----------|--------------|-----------------|-----------|
| status    | string       | success; error  | always    |
| code      | int          | [statusCode]    | always    |
| message   | string       | [statusMessage] | always    |
| data      | myipResponse | [myipResponse]  | success   |

## myipResponse

| attribute | value type   | value         |
|-----------|--------------|---------------|
| ip        | string       | IP v4 address |

## Sample

```
{  
   "status":"success",
   "code":200,
   "message":"Okay.",
   "data":{  
      "ip":"77.45.93.213"
   }
}
```

# Relevant status codes

| code | state   | message   |
|------|---------|-----------|
| 200  | success | Okay.     |

__All global status codes are relevant too.__
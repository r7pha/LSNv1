# LSN
functions:
- LSN_HTTPGET --> Securely makes a GET request to a remote server.
Ex:
```lua
LSN_REQUEST("Url here");
-- 2
local Response = LSN_REQUEST("Url here");
loadstring(Response)()
print(Response)
```

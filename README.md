# LSN
functions:
- LSN_HTTPGET --> Securely makes a GET request to a remote server.
Ex:
```lua
LSN_REQUEST("https://pastebin.com/raw/vro");
-- 2
local Response = LSN_REQUEST("https://pastebin.com/raw/vro");
print(Response)
```

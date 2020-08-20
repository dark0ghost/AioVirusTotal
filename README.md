# AioVirusTotal
__lib implementing__ [service](https://virustotal.com/)

# dep
**python>=3.7**
**aiohttp>=3.6**

# how use
```python
from virustotal import  Virustotal
import aiohttp

async def main():
   session: aiohttp.ClientSession = aiohttp.ClientSession()
   total =  Virustotal(sessiom=session,api_key="")
   await total.need_your_method()
```


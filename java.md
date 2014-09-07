Java Commands

Java system properties with -jar: 
```
java [-options] -jar jarfile [args...]
```

Java socks proxy with -jar: 
```
java -DsocksProxyHost=127.0.0.1 -DsocksProxyPort=9090 -jar jarfile [args...]
```

Java JProfiler agent instrumentation:
```
java -agentpath:[full path to JProfiler library]=[agent parameters]
```

# flutter_local_network_ios

For iOS

* Add Key `Privacy - Local Network Usage Description` to info.plist.
* Add Key `Bonjour services` Value item `_paperang._tcp`

```xml
<key>NSBonjourServices</key>
<array>
    <string>_paperang._tcp</string>
</array>
```

```xml
<key>NSLocalNetworkUsageDescription</key>
<string>是否允许使用本地网络</string>
```

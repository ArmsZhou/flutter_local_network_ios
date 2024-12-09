# flutter_local_network_ios

For iOS

* Add Key `Privacy - Local Network Usage Description` to info.plist.
* Add Key `Bonjour services` Value item `_paperang._tcp`

```xml
<key>NSBonjourServices</key>
<array>
    <string>_paperang._tcp</string>
    <string>_esp_local_ctrl._tcp</string>
    <string>_matter._tcp</string>
    <string>_matterc._udp</string>
    <string>_matterd._udp</string>
    <string>_meshcop._udp</string>
</array>
```

```xml
<key>NSLocalNetworkUsageDescription</key>
<string>是否允许使用本地网络</string>
```
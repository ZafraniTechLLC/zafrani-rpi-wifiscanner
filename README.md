# Forked from https://github.com/thingsSDK/wifiscanner

The purpose of this repo is to add an additional field to the json output for `rssi`.  Sample output will look like

```
[
    {
        rssi: -123,
        ssid: 'wifi with-n0-s3cur1ty!',
        mac: '16:0d:7f:49:da:e1',
        channel: '1',
        security: ['None']
    },
    {
        rssi: -172,
        ssid: 'WEP enabled',
        mac: '16:0d:7f:49:da:e2',
        channel: '1',
        security: ['WEP']
    },
    {
        rssi: -187,
        ssid: 'WPA1 Enabled',
        mac: '16:0d:7f:49:da:e3',
        channel: '1',
        security: ['WPA']
    },
    {
        rssi: -234,
        ssid: 'WPA1+WPA2',
        mac: '16:0d:7f:49:da:e4',
        channel: '1',
        security: ['WPA', 'WPA2'],
    },
    {
        rssi: -251,
        ssid: 'WPA2 Only',
        mac: '16:0d:7f:49:da:e5',
        channel: '1',
        security: ['WPA2']
    }
]
```


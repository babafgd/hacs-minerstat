# hacs-crypto-aggregator

An attempt to aggregate Crypto wallet balance and unpaid pool balance from various source :
- Support Ethermine pool wallet [Ethermine](https://ethermine.org/)
- An integration with [Minerstart](https://minerstat.com/) to create a sensor from your rig's hashrate.

## Usage
`configuration.yaml`:
```yaml
sensor:
  - platform: hacs-Crypto-aggregator
    name: "My Awesome Rig"
    access_key: "00000000"
    rig_name: "RIG1"
```

## Options
|Name|Type|Necessity|Default|Description|
|----|:--:|:-------:|:-----:|-----------|
|`platform`|string|**Required**|`hacs-Crypto-aggregator`|The platform name|
|`access_key`|string|**Required**||Your personal access key from https://my.minerstat.com/|
|`rig_name`|string|**Required**||The name that you defined for your rig at Minerstat|
|`name`|string|Optional|`Minerstat`|Custom name for the sensor|

## Support this project
From parent project ! hacs minterstat
**Buy me a ~~coffee~~ beer 🍺**: https://www.buymeacoffee.com/gilson

**BTC**: 33TwXHzMTpSNMJZ4JcwExLExsF3BshBUPE

**ETH**: 0xa772c6bab9d175256ff635843c461d3f65a7236b

**LTC**: M9adpiNQXsbEf7j5ZVnuDCGNoXT7oMW3vd

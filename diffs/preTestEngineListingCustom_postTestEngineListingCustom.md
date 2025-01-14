## Reserve changes

### Reserves added

#### 1INCH ([0x111111111117dC0aa78b770fA6A738034120C302](https://etherscan.io/address/0x111111111117dC0aa78b770fA6A738034120C302))

| description | value |
| --- | --- |
| decimals | 18 |
| isActive | true |
| isFrozen | false |
| supplyCap | 85,000 1INCH |
| borrowCap | 60,000 1INCH |
| debtCeiling | 0 $ |
| isSiloed | false |
| isFlashloanable | false |
| eModeCategory | 0 |
| oracle | [0x72AFAECF99C9d9C8215fF44C77B94B99C28741e8](https://etherscan.io/address/0x72AFAECF99C9d9C8215fF44C77B94B99C28741e8) |
| oracleDecimals | 18 |
| oracleDescription | 1INCH / ETH |
| oracleLatestAnswer | 0.000328918384865774 |
| usageAsCollateralEnabled | true |
| ltv | 82.5 % |
| liquidationThreshold | 86 % |
| liquidationBonus | 5 % |
| liquidationProtocolFee | 10 % |
| reserveFactor | 10 % |
| aToken | [0x7B95Ec873268a6BFC6427e7a28e396Db9D0ebc65](https://etherscan.io/address/0x7B95Ec873268a6BFC6427e7a28e396Db9D0ebc65) |
| aTokenImpl | [0x7EfFD7b47Bfd17e52fB7559d3f924201b9DbfF3d](https://etherscan.io/address/0x7EfFD7b47Bfd17e52fB7559d3f924201b9DbfF3d) |
| variableDebtToken | [0x1b7D3F4b3c032a5AE656e30eeA4e8E1Ba376068F](https://etherscan.io/address/0x1b7D3F4b3c032a5AE656e30eeA4e8E1Ba376068F) |
| variableDebtTokenImpl | [0xaC725CB59D16C81061BDeA61041a8A5e73DA9EC6](https://etherscan.io/address/0xaC725CB59D16C81061BDeA61041a8A5e73DA9EC6) |
| stableDebtToken | [0x90D9CD005E553111EB8C9c31Abe9706a186b6048](https://etherscan.io/address/0x90D9CD005E553111EB8C9c31Abe9706a186b6048) |
| stableDebtTokenImpl | [0x15C5620dfFaC7c7366EED66C20Ad222DDbB1eD57](https://etherscan.io/address/0x15C5620dfFaC7c7366EED66C20Ad222DDbB1eD57) |
| borrowingEnabled | true |
| stableBorrowRateEnabled | true |
| isBorrowableInIsolation | false |
| interestRateStrategy | [0x24701A6368Ff6D2874d6b8cDadd461552B8A5283](https://etherscan.io/address/0x24701A6368Ff6D2874d6b8cDadd461552B8A5283) |
| stableDebtTokenName | Aave Ethereum Stable Debt 1INCH |
| variableDebtTokenName | Aave Ethereum Variable Debt 1INCH |
| isPaused | false |
| aTokenName | Aave Ethereum 1INCH |
| variableDebtTokenSymbol | variableDebtEth1INCH |
| stableDebtTokenSymbol | stableDebtEth1INCH |
| aTokenSymbol | aEth1INCH |
| optimalUsageRatio | 45 % |
| maxExcessUsageRatio | 55 % |
| baseVariableBorrowRate | 0 % |
| variableRateSlope1 | 7 % |
| variableRateSlope2 | 300 % |
| baseStableBorrowRate | 9 % |
| stableRateSlope1 | 7 % |
| stableRateSlope2 | 300 % |
| optimalStableToTotalDebtRatio | 20 % |
| maxExcessStableToTotalDebtRatio | 80 % |
| interestRate | ![ir](/.assets/b5cb0fd07fde8594230045982589445fc02ace52.svg) |


## Raw diff

```json
{
  "reserves": {
    "0x111111111117dC0aa78b770fA6A738034120C302": {
      "from": null,
      "to": {
        "stableDebtTokenName": "Aave Ethereum Stable Debt 1INCH",
        "variableDebtTokenName": "Aave Ethereum Variable Debt 1INCH",
        "oracle": "0x72AFAECF99C9d9C8215fF44C77B94B99C28741e8",
        "oracleDescription": "1INCH / ETH",
        "isPaused": false,
        "isFlashloanable": false,
        "borrowingEnabled": true,
        "liquidationProtocolFee": 1000,
        "oracleLatestAnswer": 328918384865774,
        "aTokenName": "Aave Ethereum 1INCH",
        "liquidationBonus": 10500,
        "ltv": 8250,
        "stableBorrowRateEnabled": true,
        "debtCeiling": 0,
        "isFrozen": false,
        "usageAsCollateralEnabled": true,
        "eModeCategory": 0,
        "isBorrowableInIsolation": false,
        "oracleDecimals": 18,
        "symbol": "1INCH",
        "aTokenImpl": "0x7EfFD7b47Bfd17e52fB7559d3f924201b9DbfF3d",
        "stableDebtTokenImpl": "0x15C5620dfFaC7c7366EED66C20Ad222DDbB1eD57",
        "reserveFactor": 1000,
        "liquidationThreshold": 8600,
        "borrowCap": 60000,
        "variableDebtTokenSymbol": "variableDebtEth1INCH",
        "stableDebtTokenSymbol": "stableDebtEth1INCH",
        "aTokenSymbol": "aEth1INCH",
        "variableDebtTokenImpl": "0xaC725CB59D16C81061BDeA61041a8A5e73DA9EC6",
        "decimals": 18,
        "isActive": true,
        "aToken": "0x7B95Ec873268a6BFC6427e7a28e396Db9D0ebc65",
        "isSiloed": false,
        "supplyCap": 85000,
        "stableDebtToken": "0x90D9CD005E553111EB8C9c31Abe9706a186b6048",
        "variableDebtToken": "0x1b7D3F4b3c032a5AE656e30eeA4e8E1Ba376068F",
        "interestRateStrategy": "0x24701A6368Ff6D2874d6b8cDadd461552B8A5283",
        "underlying": "0x111111111117dC0aa78b770fA6A738034120C302"
      }
    }
  }
}
```
# NULS2.0 通用区块链浏览器模块
依赖 api-module

## Contribution

Contributions to NULS are welcomed! We sincerely invite developers who experienced in blockchain field to join in NULS technology community. Details: s: https://nuls.communimunity/d/9-recruitment-of-community-developers To be a great community, Nuls needs to welcome developers from all walks of life, with different backgrounds, and with a wide range of experience.

## License

Nuls is released under the [MIT](http://opensource.org/licenses/MIT) license.
Modules added in the future may be release under different license, will specified in the module library path.

## Community

- [nuls.io](https://nuls.io/)
- [@twitter](https://twitter.com/nulsservice)
- [facebook](https://www.facebook.com/nulscommunity/)
- [YouTube channel](https://www.youtube.com/channel/UC8FkLeF4QW6Undm4B3InN1Q?view_as=subscriber)
- Telegram [NULS Community](https://t.me/Nulsio)
- Telegram [NULS 中文社区](https://t.me/Nulscn)

####  


curl 'http://127.0.0.1:18004' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getAnnulizedRewardStatistical","params":[1,3],"id":736}' 

curl 'http://127.0.0.1:18003' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getAnnulizedRewardStatistical","params":[1,3],"id":736}' 

curl 'http://127.0.0.1:18003' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getChainInfo","params":[3],"id":736}' -s | json

ubuntu@db1:/data/nuls/NULS_WALLET$ 
curl 'http://127.0.0.1:18003' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getInfo","params":[3],"id":736}' -s | json
{ubuntu@db1:/data/nuls/NULS_WALLET$ curl 'http://127.0.0.1:18003' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getInfo","params":[3],"id":736}' -s | json
{
  "jsonrpc": "2.0",
  "id": "736",
  "result": {
    "networkHeight": 534,
    "isRunSmartContract": true,
    "chainId": 3,
    "agentAsset": null,
    "localHeight": 534,
    "magicNumber": 1000,
    "defaultAsset": {
      "symbol": "SAMO",
      "chainId": 3,
      "assetId": 1,
      "decimals": 8
    },
    "isRunCrossChain": true
  }
}



curl 'http://127.0.0.1:18003' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getOtherChainList","params":[1],"id":736}' -s | json
{
  "jsonrpc": "2.0",
  "id": "736",
  "result": [
    {
      "chainName": null,
      "chainId": 2
    }
  ]
}

curl 'http://127.0.0.1:18003' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getBestBlockHeader","params":[3],"id":73116}' -s |json


curl 'http://127.0.0.1:18003' -H 'Content-Type: application/json;charset=UTF-8' --data-binary '{"jsonrpc":"2.0","method":"getHeaderByHeight","params":[3,2],"id":73116}' -s |json

import c115b83c2135d6b00044057a64ae52d8a7d7aba53f43da416983c721f397aaf0
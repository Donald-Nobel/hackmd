
# Admin Of Contracts

## Check List
| Project         | Ethereum         | Arbi   | Op      | BSC    | Poly | Avax | Kava   |
| --------------- | ---------------- | ------ | ------- | ------ | ---- | ---- | ------ |
| Lending         | T                | T      | T       | T      | T    | T    | 0x376E |
| Liqee           | E                | -      | -       | E      | -    | -    | -      |
| Vaults          | T                | T      | T       | T      | -    | -    | -      |
| Entrofi         | -                | -      | -       | T      | -    | -    | -      |
| PDLP            | M                | M      | M       | M      | M    | M    | 0x376E |
| POO             | M                | M      | M       | M      | -    | -    | -      |
| Bridge          | E                | E      | E       | -      | -    | -    | -      |
| Aggregator      | M                | M      | M       | M      | -    | -    | -      |
| LSR             | T                | T      | T       | T      | T    | -    | -      |
| LiquiditySwap   | T                | T      | -       | -      | -    | -    | -      |
| Oracle          | T                | T      | T       | T      | T    | -    | -      |
| Loopfi          | 0xbe5C&D(Saddle) | 0xbe5C | D(Velo) | -      | -    | -    | -      |
| sDF             | T                | -      | -       | -      | -    | -    | -      |
| veDF            | T                | -      | -       | -      | -    | -    | -      |
| LiquidityMining | T                | T      | T&M(OP) | T      | -    | -    | -      |
| USDx            | 0x0Eb7           | -      | -       | -      | -    | -    | -      |
| USR             | 0xD6A6           | -      | -       | -      | -    | -    | -      |
| GOLDx           | 0xcc0A           | -      | -       | -      | -    | -    | -      |
| dToken          | 0x218c           | -      | -       | 0x218c | -    | -    | -      |
| Staking         | 0x3775           | -      | -       | -      | -    | -    | -      |


> **Notes**: 
> "E" means the ownership is owned by external party, for example: layer2 governance for bridge
> "M" means multisig
> "T" means timelock
> "D" means deployer

---

## Details

### Mainnet
* multisig: [0x145c79A1F0e1Ad5ad7fC8d99548a02A07B24F8FD](https://etherscan.io/address/0x145c79A1F0e1Ad5ad7fC8d99548a02A07B24F8FD)
* timelock: [0x17e66B1e0260C930bfA567ff3ab5c71794279b94](https://etherscan.io/address/0x17e66B1e0260C930bfA567ff3ab5c71794279b94)
> * all external owners here
* 0x218C: [0x218C473DC036e77F9EC18b857CC872362964304F](https://etherscan.io/address/0x218C473DC036e77F9EC18b857CC872362964304F)
* 0x825C: [0x825C5C9129B6BD74fF1c70cF63B291D239836848](https://etherscan.io/address/0x825C5C9129B6BD74fF1c70cF63B291D239836848)
* 0x0Eb7: [0x0Eb7FC2A5FB656944e31C59A68151159C0745998](https://etherscan.io/address/0x0Eb7FC2A5FB656944e31C59A68151159C0745998)
* 0xD6A6: [0xD6A68e5fb7B407F0FB2b4408a5F727CD11b8FDA6](https://etherscan.io/address/0xD6A68e5fb7B407F0FB2b4408a5F727CD11b8FDA6)
* 0xcc0A: [0xcc0Ab3d517Cb4926D44F9C203Cd40051Ce3a32C8](https://etherscan.io/address/0xcc0Ab3d517Cb4926D44F9C203Cd40051Ce3a32C8)
* 0x3775: [0x377598d56030b2d6a9E83f20d44ba3B10ddFA2D5](https://etherscan.io/address/0x377598d56030b2d6a9E83f20d44ba3B10ddFA2D5)
* 0xbD20: [0xbD206d0677BEf61f3abA309f84473fCF5C44C880](https://etherscan.io/address/0xbD206d0677BEf61f3abA309f84473fCF5C44C880)
* 0x1477: [0x1477959Bcb3B6782f278b798b4F80cAf4Cf252c6](https://etherscan.io/address/0x1477959Bcb3B6782f278b798b4F80cAf4Cf252c6)
* 0xbe5C: [0xbe5C18530a79Fd12aA788904e40404D713b9D11D](https://etherscan.io/address/0xbe5C18530a79Fd12aA788904e40404D713b9D11D)
> * deprecated deployer derivations
* deployer: [0x377598d56030b2d6a9E83f20d44ba3B10ddFA2D5](https://etherscan.io/address/0x377598d56030b2d6a9e83f20d44ba3b10ddfa2d5)
* dToken rebalancer: [0x44f8400CBAb72432CAab7b175A86029d993BD6Ca](https://etherscan.io/address/0x44f8400CBAb72432CAab7b175A86029d993BD6Ca)
* lendfme deployer: [0xd30076B706fa0425BC52d0739224fe8ef1ae7c81](https://etherscan.io/address/0xd30076B706fa0425BC52d0739224fe8ef1ae7c81)
* USDx deployer: [0x10EFe6b046eaBE33a86d52B78ED178236CFF46d8](https://etherscan.io/address/0x10EFe6b046eaBE33a86d52B78ED178236CFF46d8)
* lendingV2 deployer: [0x6F43161E3A56501ea14B2901132A4d9F0945E179](https://etherscan.io/address/0x6F43161E3A56501ea14B2901132A4d9F0945E179)
* lendingV2 deployer(BSC): [0x4375c89AF5b4aF46791b05810C4B795A0470207F](https://etherscan.io/address/0x4375c89AF5b4aF46791b05810C4B795A0470207F)
* liqee pauser: [0x2929F07fF145a21b6784fE923b24F3ED38C3a5c3](https://etherscan.io/address/0x2929F07fF145a21b6784fE923b24F3ED38C3a5c3)
* dforce pauser: [0x491C366614b971596cFf5570665DD9d24966de49](https://etherscan.io/address/0x491C366614b971596cFf5570665DD9d24966de49)
* dforce poster: [0x5c5bFFdB161E637B7f555CC122831126e02270d5](https://etherscan.io/address/0x5c5bFFdB161E637B7f555CC122831126e02270d5)


### Arbitrum
* multisig: [0x9d82033BB36217B44567edC635bE926f74D1b76f](https://arbiscan.io/address/0x9d82033BB36217B44567edC635bE926f74D1b76f)
* timelock: [0x1E96e916A64199069CcEA2E6Cf4D63d30a61b93d](https://arbiscan.io/address/0x1E96e916A64199069CcEA2E6Cf4D63d30a61b93d)

### Optimism
* multisig: [0xebAA48d1C4129E93A1d286B01B56cc4981c30004](https://optimistic.etherscan.io/address/0xebAA48d1C4129E93A1d286B01B56cc4981c30004)
* timelock: [0x0D535ca4C27f0C25a20e2D474Ee3E99c1316BAfe](https://optimistic.etherscan.io/address/0x0D535ca4C27f0C25a20e2D474Ee3E99c1316BAfe)

### BSC
* multisig: [0x4006E4A788edFf483B5a0C90ca9AF9C0A497072b](https://bscscan.com/address/0x4006E4A788edFf483B5a0C90ca9AF9C0A497072b)
* timelock: [0x8C3984Fb0F649c304D68DB69457DBF137D156D7a](https://bscscan.com/address/0x8C3984Fb0F649c304D68DB69457DBF137D156D7a)

### Polygon
* multisig: [0xD111d78ceE08842624aDE8ADE280960083c0f3A9](https://polygonscan.com/address/0xD111d78ceE08842624aDE8ADE280960083c0f3A9)
* timelock: [0x1C4d5eCFBf2AF57251f20a524D0f0c1b4f6ED1C9](https://polygonscan.com/address/0x1C4d5eCFBf2AF57251f20a524D0f0c1b4f6ED1C9)

### Avalanche
* multisig: [0x2bC641C7dC402d114f94A96b809a432B91D7fDb6](https:///snowtrace.io/address/0x2bC641C7dC402d114f94A96b809a432B91D7fDb6)
* timelock: [0xB9498979c686f6662D916ceC08A9B759d6783E9C](https:///snowtrace.io/address/0xB9498979c686f6662D916ceC08A9B759d6783E9C)

### Kava
* multisig(deployer): [0xDE6D6f23AabBdC9469C8907eCE7c379F98e4Cb75](https://explorer.kava.io/address/0xDE6D6f23AabBdC9469C8907eCE7c379F98e4Cb75)
* timelock: [0x5237d212F9BbC83d91c2cbd810D2b07808d94f08](https://explorer.kava.io/address/0x5237d212F9BbC83d91c2cbd810D2b07808d94f08)
* 0x376E: [0x376E6832830eC117000dF9106DD8E433E1d40d90](https://explorer.kava.io/address/0x376E6832830eC117000dF9106DD8E433E1d40d90)
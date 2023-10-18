---
id: "typechain.factories.contracts.verifiers.UserStateTransitionVerifier__factory"
title: "Class: UserStateTransitionVerifier__factory"
sidebar_label: "UserStateTransitionVerifier__factory"
custom_edit_url: null
---

[contracts](../namespaces/typechain.factories.contracts.md).[verifiers](../namespaces/typechain.factories.contracts.verifiers.md).UserStateTransitionVerifier__factory

## Hierarchy

- `ContractFactory`

  ↳ **`UserStateTransitionVerifier__factory`**

## Constructors

### constructor

• **new UserStateTransitionVerifier__factory**(`...args`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `UserStateTransitionVerifierConstructorParams` |

#### Overrides

ContractFactory.constructor

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:50

## Properties

### bytecode

• `Readonly` **bytecode**: `string`

#### Inherited from

ContractFactory.bytecode

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:139

___

### interface

• `Readonly` **interface**: `Interface`

#### Inherited from

ContractFactory.interface

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:138

___

### signer

• `Readonly` **signer**: `Signer`

#### Inherited from

ContractFactory.signer

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:140

___

### abi

▪ `Static` `Readonly` **abi**: readonly [{ `inputs`: readonly [{ `internalType`: ``"uint256[]"`` = "uint256[]"; `name`: ``"input"`` = "input"; `type`: ``"uint256[]"`` = "uint256[]" }, { `internalType`: ``"uint256[8]"`` = "uint256[8]"; `name`: ``"_proof"`` = "\_proof"; `type`: ``"uint256[8]"`` = "uint256[8]" }] ; `name`: ``"verifyProof"`` = "verifyProof"; `outputs`: readonly [{ `internalType`: ``"bool"`` = "bool"; `name`: ``""`` = ""; `type`: ``"bool"`` = "bool" }] ; `stateMutability`: ``"view"`` = "view"; `type`: ``"function"`` = "function" }] = `_abi`

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:78

___

### bytecode

▪ `Static` `Readonly` **bytecode**: ``"0x608060405234801561001057600080fd5b506113b7806100206000396000f3fe608060405234801561001057600080fd5b506004361061002b5760003560e01c80637004914414610030575b600080fd5b61004361003e3660046111dd565b610057565b604051901515815260200160405180910390f35b600061006161106a565b6040805180820182528435815260208086013581830152908352815160808082018452868401358285019081526060808901359084015282528351808501855290870135815260a08701358184015281830152838201528151808301835260c0860135815260e0860135918101919091529082015260006100e06106de565b6040805180820190915260008082526020820152835151919250907f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd4711610188576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601760248201527f76657269666965722d61582d6774652d7072696d652d7100000000000000000060448201526064015b60405180910390fd5b8251602001517f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd4711610216576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601760248201527f76657269666965722d61592d6774652d7072696d652d71000000000000000000604482015260640161017f565b602083015151517f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd47116102a5576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601860248201527f76657269666965722d6258302d6774652d7072696d652d710000000000000000604482015260640161017f565b6020838101510151517f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd4711610336576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601860248201527f76657269666965722d6259302d6774652d7072696d652d710000000000000000604482015260640161017f565b6020838101515101517f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd47116103c7576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601860248201527f76657269666965722d6258312d6774652d7072696d652d710000000000000000604482015260640161017f565b60208381015181015101517f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd471161045a576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601860248201527f76657269666965722d6259312d6774652d7072696d652d710000000000000000604482015260640161017f565b6040830151517f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd47116104e8576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601760248201527f76657269666965722d63582d6774652d7072696d652d71000000000000000000604482015260640161017f565b7f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd4783604001516020015110610579576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601760248201527f76657269666965722d63592d6774652d7072696d652d71000000000000000000604482015260640161017f565b60005b600681101561068b577f30644e72e131a029b85045b68181585d2833e84879b9709143e1f593f00000018888838181106105b8576105b861126d565b9050602002013510610626576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601f60248201527f76657269666965722d6774652d736e61726b2d7363616c61722d6669656c6400604482015260640161017f565b61067782610672856080015184600161063f91906112cb565b6007811061064f5761064f61126d565b60200201518b8b868181106106665761066661126d565b90506020020135610b3e565b610bf9565b915080610683816112e4565b91505061057c565b5060808201515161069d908290610bf9565b90506106d36106af8460000151610cb7565b84602001518460000151856020015185876040015189604001518960600151610d71565b979650505050505050565b6106e66110bb565b6040805180820182527f2d4d9aa7e302d9df41749d5507949d05dbea33fbb16c643b22f599a2be6df2e281527f14bedd503c37ceb061d8ec60209fe345ce89830a19230301f076caff004d19266020808301919091529083528151608080820184527f0967032fcbf776d1afc985f88877f182d38480a653f2decaa9794cbc3bf3060c8285019081527f0e187847ad4c798374d0d6732bf501847dd68bc0e071241e0213bc7fc13db7ab606080850191909152908352845180860186527f304cfbd1e08a704a99f5e847d93f8c3caafddec46b7a0d379da69a4d112346a781527f1739c1b1a457a8c7313123d24d2f9192f896b7c63eea05a9d57f06547ad0cec8818601528385015285840192909252835180820185527f198e9393920d483a7260bfb731fb5d25f1aa493335a9e71297e485b7aef312c28186018181527f1800deef121f1e76426a00665e5c4479674322d4f75edadd46debd5cd992f6ed838601819052908352865180880188527f090689d0585ff075ec9e99ad690c3395bc4b313370b38ef355acdadcd122975b8082527f12c85ea5db8c6deb4aab71808dcb408fe3d1e7690c43d37b4ce6cc0166fa7daa8289018190528589019290925289890194909452875180860189528089019384528087019290925291815286518088018852928352828601919091528085019190915282860152835180850185527f057c6a78a89989fd07a46e4ca7f9dad5622b06bb9b74bc81a119cb4e3f157f6281527f29301c9b7dadf6ad3235eb111a85b226a391ef7e756cbcdacc79e6397fc5eb2c81850152818601805191909152845180860186527f178ad420673a11731f2b0b6735915599944f1e7dd62def30b61208fb0bf16b6081527f17edcd6d97ea75fe1d9a0f53c45c8a13ef8b665be9316e2d4b868e1f9367e032818601528151850152845180860186527f1d5a2e18061203d9491e502f500fe564b31de9ea744b0f79b9498fb0b2bfb49c81527f2b51a9b1d710a2606988eb04052822668cf6759184308ab1db08eedd1ce0ece3818601528151860152845180860186527f0c77790a726a1f64a3f4d0564eac029668227a211a398ec6e88b440a1ea4063881527f29022bc847f7a8ff601a9810823e4be917559865883deec314f7d0c2233e7ee781860152815190930192909252835180850185527f0d9022f952242d996f25e9887d3c0473c9621bb7a6ed92c6a8fdb4cf6d15e89e81527f2e7c1a9febd32ce2c6b8b85a0b189e60265556f4cab3a1b712880920760ae5c281850152825190910152825180840184527f0d142b7f833fcfe45e0c8905d90df1db1579c56f46d1292a95db4fe8d45e2b6481527f1d0c737a3c0964e6f28e759bccd10858c61f6f81968a7e862b326a95e592f8ae81840152815160a0015282518084019093527f22e408103648c74d99a6ef88f2dc5480ad3ab7ac9da98b7b2d3817b253a6e41583527f1f2216cb94e3cb31d3f87edfa13fd45018ca2d4c6c920978fc3e0e2c4615e704918301919091525160c0015290565b6040805180820190915260008082526020820152610b5a61110c565b835181526020808501519082015260408101839052600060608360808460076107d05a03fa90508080610b8957fe5b5080610bf1576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601260248201527f70616972696e672d6d756c2d6661696c65640000000000000000000000000000604482015260640161017f565b505092915050565b6040805180820190915260008082526020820152610c1561112a565b8351815260208085015181830152835160408301528301516060808301919091526000908360c08460066107d05a03fa90508080610c4f57fe5b5080610bf1576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601260248201527f70616972696e672d6164642d6661696c65640000000000000000000000000000604482015260640161017f565b60408051808201909152600080825260208201528151158015610cdc57506020820151155b15610cfa575050604080518082019091526000808252602082015290565b6040518060400160405280836000015181526020017f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd478460200151610d3f919061131c565b610d69907f30644e72e131a029b85045b68181585d97816a916871ca8d3c208c16d87cfd47611357565b905292915050565b60408051608080820183528a825260208083018a90528284018890526060808401879052845192830185528b83528282018a9052828501889052820185905283516018808252610320820190955260009491859190839082016103008036833701905050905060005b6004811015610fc5576000610df082600661136a565b9050858260048110610e0457610e0461126d565b60200201515183610e168360006112cb565b81518110610e2657610e2661126d565b602002602001018181525050858260048110610e4457610e4461126d565b60200201516020015183826001610e5b91906112cb565b81518110610e6b57610e6b61126d565b602002602001018181525050848260048110610e8957610e8961126d565b6020020151515183610e9c8360026112cb565b81518110610eac57610eac61126d565b602002602001018181525050848260048110610eca57610eca61126d565b6020020151516001602002015183610ee38360036112cb565b81518110610ef357610ef361126d565b602002602001018181525050848260048110610f1157610f1161126d565b602002015160200151600060028110610f2c57610f2c61126d565b602002015183610f3d8360046112cb565b81518110610f4d57610f4d61126d565b602002602001018181525050848260048110610f6b57610f6b61126d565b602002015160200151600160028110610f8657610f8661126d565b602002015183610f978360056112cb565b81518110610fa757610fa761126d565b60209081029190910101525080610fbd816112e4565b915050610dda565b50610fce611148565b6000602082602086026020860160086107d05a03fa90508080610fed57fe5b5080611055576040517f08c379a000000000000000000000000000000000000000000000000000000000815260206004820152601560248201527f70616972696e672d6f70636f64652d6661696c65640000000000000000000000604482015260640161017f565b505115159d9c50505050505050505050505050565b6040805160a081019091526000606082018181526080830191909152815260208101611094611166565b81526020016110b6604051806040016040528060008152602001600081525090565b905290565b6040805160e08101909152600060a0820181815260c08301919091528152602081016110e5611166565b81526020016110f2611166565b81526020016110ff611166565b81526020016110b6611186565b60405180606001604052806003906020820280368337509192915050565b60405180608001604052806004906020820280368337509192915050565b60405180602001604052806001906020820280368337509192915050565b60405180604001604052806111796111bf565b81526020016110b66111bf565b6040518060e001604052806007905b60408051808201909152600080825260208201528152602001906001900390816111955790505090565b60405180604001604052806002906020820280368337509192915050565b60008060006101208085870312156111f457600080fd5b843567ffffffffffffffff8082111561120c57600080fd5b818701915087601f83011261122057600080fd5b81358181111561122f57600080fd5b8860208260051b850101111561124457600080fd5b60208301965080955050505085818601111561125f57600080fd5b506020840190509250925092565b7f4e487b7100000000000000000000000000000000000000000000000000000000600052603260045260246000fd5b7f4e487b7100000000000000000000000000000000000000000000000000000000600052601160045260246000fd5b808201808211156112de576112de61129c565b92915050565b60007fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff82036113155761131561129c565b5060010190565b600082611352577f4e487b7100000000000000000000000000000000000000000000000000000000600052601260045260246000fd5b500690565b818103818111156112de576112de61129c565b80820281158282048414176112de576112de61129c56fea2646970667358221220580ecf7ff8776a06f5e61def2deb226740911d18bb08a7fcfc167f45f7a9241e64736f6c63430008130033"``

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:77

## Methods

### attach

▸ **attach**(`address`): [`UserStateTransitionVerifier`](../interfaces/typechain.contracts.verifiers.UserStateTransitionVerifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

#### Returns

[`UserStateTransitionVerifier`](../interfaces/typechain.contracts.verifiers.UserStateTransitionVerifier.md)

#### Overrides

ContractFactory.attach

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:70

___

### connect

▸ **connect**(`signer`): [`UserStateTransitionVerifier__factory`](typechain.factories.contracts.verifiers.UserStateTransitionVerifier__factory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `signer` | `Signer` |

#### Returns

[`UserStateTransitionVerifier__factory`](typechain.factories.contracts.verifiers.UserStateTransitionVerifier__factory.md)

#### Overrides

ContractFactory.connect

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:73

___

### deploy

▸ **deploy**(`overrides?`): `Promise`<[`UserStateTransitionVerifier`](../interfaces/typechain.contracts.verifiers.UserStateTransitionVerifier.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `overrides?` | `Overrides` & { `from?`: `string`  } |

#### Returns

`Promise`<[`UserStateTransitionVerifier`](../interfaces/typechain.contracts.verifiers.UserStateTransitionVerifier.md)\>

#### Overrides

ContractFactory.deploy

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:58

___

### getDeployTransaction

▸ **getDeployTransaction**(`overrides?`): `TransactionRequest`

#### Parameters

| Name | Type |
| :------ | :------ |
| `overrides?` | `Overrides` & { `from?`: `string`  } |

#### Returns

`TransactionRequest`

#### Overrides

ContractFactory.getDeployTransaction

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:65

___

### connect

▸ `Static` **connect**(`address`, `signerOrProvider`): [`UserStateTransitionVerifier`](../interfaces/typechain.contracts.verifiers.UserStateTransitionVerifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `signerOrProvider` | `Provider` \| `Signer` |

#### Returns

[`UserStateTransitionVerifier`](../interfaces/typechain.contracts.verifiers.UserStateTransitionVerifier.md)

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:82

___

### createInterface

▸ `Static` **createInterface**(): `UserStateTransitionVerifierInterface`

#### Returns

`UserStateTransitionVerifierInterface`

#### Defined in

packages/contracts/typechain/factories/contracts/verifiers/UserStateTransitionVerifier__factory.ts:79

___

### fromSolidity

▸ `Static` **fromSolidity**(`compilerOutput`, `signer?`): `ContractFactory`

#### Parameters

| Name | Type |
| :------ | :------ |
| `compilerOutput` | `any` |
| `signer?` | `Signer` |

#### Returns

`ContractFactory`

#### Inherited from

ContractFactory.fromSolidity

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:148

___

### getContract

▸ `Static` **getContract**(`address`, `contractInterface`, `signer?`): `Contract`

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `contractInterface` | `ContractInterface` |
| `signer?` | `Signer` |

#### Returns

`Contract`

#### Inherited from

ContractFactory.getContract

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:154

___

### getContractAddress

▸ `Static` **getContractAddress**(`tx`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | `Object` |
| `tx.from` | `string` |
| `tx.nonce` | `number` \| `BytesLike` \| `BigNumber` |

#### Returns

`string`

#### Inherited from

ContractFactory.getContractAddress

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:150

___

### getInterface

▸ `Static` **getInterface**(`contractInterface`): `Interface`

#### Parameters

| Name | Type |
| :------ | :------ |
| `contractInterface` | `ContractInterface` |

#### Returns

`Interface`

#### Inherited from

ContractFactory.getInterface

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:149
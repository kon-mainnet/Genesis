Bridge mode: ARBITRARY_MESSAGE
========================================
Deploying Arbitrary Message Bridge at Home
========================================

deploying storage for home validators
pending txHash 0x6478e402d186b5a07e2f0109d334887743bee098efd88fdc1facec0d5e0ff01a
[Home] BridgeValidators Storage:  0xeec27A776CB3b9885c85bfBCa01807Ae1aBeb18e

deploying implementation for home validators
pending txHash 0x329d5904f0a6115b7471c12dae8ded0807f41119b752260e7ef6931c9daa08f6
[Home] BridgeValidators Implementation:  0xdd65643D57E6b169361B46500DEb55CAdE6C8D22

hooking up eternal storage to BridgeValidators
pending txHash 0x717d7d40bd1c0ec47050284e0fd09dc7b3cda0c78f9ea476208cb0866b55bf18

initializing Home Bridge Validators with following parameters:

REQUIRED_NUMBER_OF_VALIDATORS: 1, VALIDATORS: 0xFd7484171858Eee93f0a186541465683c90d4d10, VALIDATORS_OWNER: 0xFd7484171858Eee93f0a186541465683c90d4d10
pending txHash 0x1d5dd7e115236ba4a55b4004f0623402e48351dd8b73f2a17d4fed48772183f6
transferring proxy ownership to multisig for Validators Proxy contract
pending txHash 0x85594b1a44eb66d49f151d20367af144c3324361af038783483a18ac849d8ba2

deploying HomeAMBridge storage

pending txHash 0x00b8df7fab1f7e6a474539a240f3795e489488189a24f619c3bde10638e3b93e
[Home] HomeAMBridge Storage:  0xba8A15f4142C225F9e3e02cd01311ACd94Cf6eC6

deploying HomeAMBridge implementation

pending txHash 0xa29b3d973c4ba3daf8f8dbd6293f732507b16d3e8422d1f3048c0fb674803cf5
[Home] HomeAMBridge Implementation:  0xbC60a5d0e4258F8D51F6f9BeD83F1dD25f31714F

hooking up HomeAMBridge storage to HomeAMBridge implementation
pending txHash 0x97e572782d3a4dcd71bcf2a152c963f20f6568f346516ee644b53d3fa8307af7

initializing Home Bridge with following parameters:

SOURCE_CHAIN_ID: 17217, DESTINATION_CHAIN_ID: 8217, Home Validators: 0xeec27A776CB3b9885c85bfBCa01807Ae1aBeb18e,
  HOME_MAX_AMOUNT_PER_TX (gas limit per call): 20000000,
  HOME_GAS_PRICE: 0, HOME_REQUIRED_BLOCK_CONFIRMATIONS : 1

pending txHash 0xa45b09eb67e5be156187a6369cfad5a1feedba418dcf704392a614f6485e5428
transferring proxy ownership to multisig for Home bridge Proxy contract
pending txHash 0xf1a845a988fa1b660873b713bde87d2e0cfb3bf7f0a8d07135c9da4a56e3ba1e

Deployment of Arbitrary Message Bridge at Home completed

========================================
Deploying Arbitrary Message Bridge at Foreign
========================================

deploying storage for foreign validators
pending txHash 0x2746740f470d71d6b91b515fbaeeea57f0b73d3d4711f6f609f33efebbd3b0f9
[Foreign] BridgeValidators Storage:  0x94a54B60078e4aB4eeB0c01424e4669e3fAc143A

deploying implementation for foreign validators
pending txHash 0x7530e078e8d004bad32a918c8724b0febb5337384521d1f22ae3d451e9fbe15d
[Foreign] BridgeValidators Implementation:  0xf661A82C4496C36C6DdaEb7297c7Ba4aA1c8d39f

hooking up eternal storage to BridgeValidators
pending txHash 0x8f0c8609f828ae09da898be38474f38fe19138651ff38e9923a39d67b7a62836

initializing Foreign Bridge Validators with following parameters:

REQUIRED_NUMBER_OF_VALIDATORS: 1, VALIDATORS: 0xFd7484171858Eee93f0a186541465683c90d4d10, VALIDATORS_OWNER: 0xFd7484171858Eee93f0a186541465683c90d4d10
pending txHash 0x9c94f307ee27282dc354faa65ad613ad1e804b14c6768af8c508b8198cfa654f

Transferring ownership of ValidatorsProxy

pending txHash 0x18e895831af009c365248a7f831c5b9d873effb5e3646108f9b0d0c3b19aa310

deploying ForeignAMBridge storage

pending txHash 0xc36eab553cac91a0d1920ab26cd5e6f81c114a9b90d3a4fb27a49a0a9a6d21df
[Foreign] ForeignAMBridge Storage:  0x5da9c3F9f33590aeAcFc00c3bc55bC72F7A3b171

deploying ForeignAMBridge implementation

pending txHash 0xc25f29ca4f2db0ea1a92713ba095e98606eb44983fb87c86f8d457e625cc12dd
[Foreign] ForeignAMBridge Implementation:  0xb73CF53c68928164fD357F629481F0c0b7337327

hooking up ForeignAMBridge storage to ForeignAMBridge implementation
pending txHash 0xb2e456c5999c240f7f989bafaf04739dd135ff0c4d798d22d72c09c16102b90d

initializing Foreign Bridge with following parameters:


initializing Foreign Bridge with following parameters:

SOURCE_CHAIN_ID: 8217, DESTINATION_CHAIN_ID: 17217, Foreign Validators: 0x94a54B60078e4aB4eeB0c01424e4669e3fAc143A,
  FOREIGN_MAX_AMOUNT_PER_TX (gas limit per call): 50000000000,
  FOREIGN_GAS_PRICE: 500000000000, FOREIGN_REQUIRED_BLOCK_CONFIRMATIONS : 1

pending txHash 0x7700fc339cd5bb4e673ad03dd89efdc0cb300d0df66e919d8effd68d86bfef10
transferring proxy ownership to multisig for Foreign bridge Proxy contract
pending txHash 0x8c7de7f9695bf280a5f3840c50d6601b74884a9b2b6e1c38f2f44849de397498

Deployment of Arbitrary Message Bridge at Foreign completed


Deployment has been completed.


[   Home  ] HomeBridge: 0xba8A15f4142C225F9e3e02cd01311ACd94Cf6eC6 at block 432233
[ Foreign ] ForeignBridge: 0x5da9c3F9f33590aeAcFc00c3bc55bC72F7A3b171 at block 115056515
Contracts Deployment have been saved to `bridgeDeploymentResults.json`
{
    "homeBridge": {
        "address": "0xba8A15f4142C225F9e3e02cd01311ACd94Cf6eC6",
        "deployedBlockNumber": 432233
    },
    "foreignBridge": {
        "address": "0x5da9c3F9f33590aeAcFc00c3bc55bC72F7A3b171",
        "deployedBlockNumber": 115056515
    }
}


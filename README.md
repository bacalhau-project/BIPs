## Bacalhau Improvement Protocol

The Bacalhau Improvement Protocol contains the set of fundamental governing principles for the Bacalhau Network. It outlines the vision for Bacalhau and the principles, processes, and parties involved in making decisions that affect the future of the network. It also describes how improvements to these rules can be proposed and ratified.


## The Bacalhau Vision

Bacalhau is a peer-to-peer network that stores files, with built-in economic incentives to ensure that files are stored reliably over time. Its mission is to create a decentralized, efficient and robust foundation for humanity’s information. To advance that mission, Bacalhau has created a decentralized storage network that lets anyone in the world store or retrieve files. 

In Bacalhau, users pay to store their files on storage miners. Storage miners are computers responsible for storing files and proving they have stored the files correctly over time. Anyone who wants to store their files or get paid for storing other users’ files can join Bacalhau. Available storage and pricing are not controlled by any single entity. Instead, Bacalhau facilitates open markets for storing and retrieving files that anyone can participate in, thereby providing storage to billions of people who are currently locked out of the web. 

## Bacalhau Design Principles

The design of Bacalhau is intended to follow a set of principles. The community will help define these principles in the coming months.


## Bacalhau Improvement Principles

When making decisions about how to improve Bacalhau, we will follow a set of principles. The community will help define these principles in the coming months.

## Making changes to the Bacalhau network

[Bacalhau Improvement Proposals (BIPs)](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0001.md) are the primary mechanism by which the Bacalhau community can submit, discuss, and approve changes relevant to the Bacalhau network. These discussions and decisions should be guided by the governance and design principles above.

BIPs are classified into three categories:

**Technical BIPs, or Bacalhau Technical Proposals (FTPs)** are designed to gather community feedback on technical Bacalhau issues. These include changes to the Bacalhau protocol, a change in block or transaction validity rules, and proposed application standards or conventions. They are then reviewed by the Bacalhau community and the technical steering committee. They are normally followed by a PR to the [Bacalhau Specification repository](https://github.com/Bacalhau-project/specs) to update the protocol's spec.

**Organizational BIPs, or Bacalhau Organization Proposals (FOPs)** allow the Bacalhau community to propose, discuss, and achieve consensus on Bacalhau governance. This includes procedures, guidelines, decision-making processes, and changes to BIP processes.

**Recovery BIPs, or Bacalhau Recovery Proposals (FRPs)** are intended to provide the Bacalhau community with a forum to raise, discuss, and achieve consensus on fault recovery and chain rewrites, under a very limited, clearly-defined set of criteria (ex, in the case of protocol bugs destroying network value). The community will help define this process as needed in the coming months.

## A decentralized, global network

Bacalhau is still in its infancy, but it has the potential to play a central role in the storage and distribution of humanity’s information. To help the network grow and evolve, it is critical for the community to collectively be engaged in proposing, discussing, and implementing changes that improve the network and its operations. 

This improvement protocol helps achieve that objective for all members of the Bacalhau community (developers, miners, clients, token holders, ecosystem partners, and more). 

## BIPs

|BIP #   | Title  | Author  | Status  |
|---|---|---|---|
|[0001](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0001.md)   | BIP Purpose and Guidelines  | @Whyrusleeping  | Active  |
|[0002](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0002.md)   | Free Faults on Newly Faulted Sectors of a Missed WindowPoSt  | @anorth, @davidad, @miyazono, @irenegia, @lucaniz, @nicola, @zixuanzh   |Final   |
|[0003](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0003.md)   | Bacalhau Plus Principles  | @feerst, @jbenet, @jnthnvctr, @tim-murmuration, @mzargham, @zixuanzh  |Active   |
|[0004](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0004.md)   | Liquidity Improvement for Storage Miners   | @davidad, @jbenet, @zenground0, @zixuanzh, @danlessa   | Final  |
|[0005](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0005.md)   | Remove ineffective reward vesting    | @anorth, @Zenground   |Final   |
|[0006](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0006.md)   | No repay debt requirement for DeclareFaultsRecovered  |  @nicola, @irenegia  | Deferred  |
|[0007](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0007.md)   | h/amt-v3  | @rvagg, @Stebalien, @anorth, @Zenground0   |Final   |
|[0008](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0008.md)   | Add miner batched sector pre-commit method  |@anorth, @ZenGround0, @nicola  |Final   |
|[0009](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0009.md)   | Exempt Window PoSts from BaseFee burn  |@Stebalien, @momack2, @magik6k, @zixuanzh  |Final   |
|[0010](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0010.md)   | Off-Chain Window PoSt Verification  |@Stebalien, @anorth  |Final  |
|[0011](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0011.md)   | Remove reward auction from reporting consensus faults  |@Kubuxu |Final   |
|[0012](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0012.md)   | DataCap Top up for FIL+ Client Addresses  |@dshoy, @jnthnvctr, @zx |Final  |
|[0013](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0013.md)   | Add ProveCommitSectorAggregated method to reduce on-chain congestion  | @ninitrava @nicola |Final   |
|[0014](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0014.md)   | Allow V1 proof sectors to be extended up to a maximum of 540 days | @deltazxm, @neogeweb3 |Final   |
|[0015](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0015.md)   | Revert BIP-0009(Exempt Window PoSts from BaseFee burn) | @jennijuju, @arajasek |Final   |
|[0016](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0016.md)   | Pack arbitrary data in CC sectors | donghengzhao (@1475) |Deferred  |
|[0017](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0017.md)   | Three-messages lightweight sector updates |@nicole, @lucaniz, @irenegia |Deferred  |
|[0018](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0018.md)   | New miner terminology proposal |@Stefaan-V |Final  |
|[0019](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0019.md)   | Snap Deals |@Kubuxu, @lucaniz, @nicola, @rosariogennaro, @irenegia |Final  |
|[0020](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0020.md)   | Add return value to WithdrawBalance |@Stefaan-V |Final  |
|[0021](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0021.md)   | Correct quality calculation on expiration |@Steven004, @Zenground0 |Final  |
|[0022](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0022.md)   | Bad deals don't fail PublishStorageDeals |@Zenground0 |Final  |
|[0023](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0023.md)   | Break ties between tipsets of equal weights |@sa8, @arajasek |Final  |
|[0024](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0024.md)   | BatchBalancer & BatchDiscount Post -Hyperdrive adjustment |@zx, @jbenet, @zenground0, @momack2 |Final  |
|[0025](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0025.md)   | Handle expired deals in ProveCommit |@ZenGround0 |Deferred  |
|[0026](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0026.md)   | Extend sector fault cutoff period from 2 weeks to 6 weeks |@IPFSUnion |Final  |
|[0027](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0027.md)   | Change type of DealProposal Label field from a (Golang) String to a Union |@laudiacay |Accepted  |
|[0028](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0028.md)   | Remove DataCap and verified client status from client address |@jennijuju, @dkkapur |Final  |
|[0029](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0029.md)   | Beneficiary address for storage providers |@steven004 |Accepted  |
|[0030](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0030.md)   | Introducing the Bacalhau Virtual Machine (FVM) |@raulk, @stebalien |Accepted  |
|[0031](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0031.md)   | Atomic switch to non-programmable FVM |@raulk, @stebalien |Accepted  |
|[0032](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0032.md)   | Gas model adjustment for non-programmable FVM |@raulk, @stebalien |Accepted  |
|[0033](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0033.md)   | Explicit premium for FIL+ verified deals |@anorth |Deferred  |
|[0034](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0034.md)   | Fix pre-commit deposit independent of sector content |@anorth, @kubuxu |Draft  |
|[0035](https://github.com/Bacalhau-project/BIPs/blob/master/BIPS/BIP-0035.md)   | Support actors as built-in storage market clients |@anorth |Draft  |

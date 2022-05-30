# Terra 2.0 & Phoenix Launch

![banner](launch-banner.png)

This repository contains the configuration parameters for Phoenix network, Terra's official mainnet. Phoenix is the decentralized network of nodes communicating over [Terra 2.0](https://github.com/terra-money/core).

Phoenix-1 genesis was built from [genesis-tools](https://github.com/terra-money/genesis-tools).

**[Phoenix-1](https://github.com/terra-money/mainnet/tree/master/phoenix-1) is the latest iteration of mainnet**.

## Terra community

Community channels actively being moderated are here:

- [Website](https://terra.money/)
- [Discord](https://discord.gg/bYfyhUT)
- [Telegram](https://t.me/terra_announcements)
- [Twitter](https://twitter.com/terra_money)
- [YouTube](https://goo.gl/3G4T1z)

We will be making announcements regarding network upgrades using these channels, so please stay tuned.

## Genesis

The genesis file for Phoenix-1 is available [here](https://phoenix-genesis.s3.us-west-1.amazonaws.com/genesis.json).

## Seed Nodes

We request known community members who wish to run public p2p seed nodes make pull requests to add community run seed and peer nodes below.

```
Known seed node list:
406bcf90a7b29df6ae475a1f94abe04ebde805af@phoenix.seed.stakebin.io:16656,fc608a9a117d8d2302bcd181aec34eec6bb4fa96@terra2-seed.blockpane.com:26656,8efd8248e06aabd553b56766ec2a850999d0861f@exitnode.cereslabs.io:36656,a07cec8341f149ed49f751146728cf81f83764ff@84.244.95.239:26656,024805b7600b6d2bce533906cd3b0856782395f7@94.130.33.117:26656,b4d3b21747539060b270457437ef1bf99a51c694@terra2.seed.synergynodes.com:26656,f28efad2d76857c2606f00bee014346481734ea0@116.203.29.116:46656,810d1628db9f1db56fa87a93fb6ef809c32d6325@phoenix.seed.terra.btcsecure.io:26656
```

```
Known peer list:
dc865a0d882f30e41e99ef23d9e6164163607523@54.147.79.192:26656,bdce6030a2bdebe4c660a76599fe3dee4a42d50f@35.154.54.64:26656,0f1096278efafcf3f0d3bd5b6544e6b8dcc36a0e@206.189.129.195:26656,c8ab8910e5f7bfcc6e81351eb851eb8c0540a194@exitnode.cereslabs.io:26656,33afc1c21cb225bb2cfb9700442a576bbaeb7691@163.172.100.203:26656,9038d63588e0ab421fa71582720c1efb1ee867f6@45.34.1.114:27656,daa2fd0dc725d6673e7688c9c57fc3b6d99c83c4@solarsys.noip.me:27656,331c2bbcd1aab921563dce85dedae840e1369e39@142.132.199.98:10656,91b675be5f81931375358e02ab687c88fab02e41@135.148.55.229:11656,9dc9e9b50c4cae52cdbec2034d879427b2a429ae@54.180.81.122:26656,ad825ef6b29306d80b0eb8101133cedf7933eb5e@116.203.36.94:26656,f2069012aec5ced4e88e7e4311391eabe72bb5a3@node-phoenix.terra.lunastations.online:26656,42315a8e51b51fa6e73a927f8edc9800abd41d67@65.21.89.54:27656,9fe9cc32880be11134e1ec360a61082541019233@162.55.85.23:26656,065fd6f49a4a424727433b3a8e3d5945e4935d9c@78.46.68.41:26656,9909a0fc254852005c6d382b2321008e669f7ad0@65.108.199.18:9095,5d423d17f84f25b8c2167fd8be4abd0b8ba89091@65.108.110.125:12095,1b308820fa76c033cd2e41e1a11b2533a55f4a03@65.108.10.95:17095,1903ccc818ee9923cd66078689d71000b2c6e4c9@65.108.98.218:10095,276dd792b8eb8703e65edcb5f5527d16b762191c@138.201.16.240:15095,7d7e614db9a73e1e6d7b56903ad79bfc13623783@142.132.252.8:11095,f58748aa96bd0110a1ed5c00b0fbf4e9faf92b20@18.219.130.4:26656,1e5e39efe018876c355cbb81a772668e5ce5e1ea@52.54.234.245:26656,49171079e358230f214f521b572f4b0caa4afa1b@51.222.42.166:26322,9c888a18a8c4a493830f56e4effd5da6035acfb7@141.95.66.199:26322,4ebf87085c2a3cc65d09549938985cf72a3c7734@phoenix.terra.kkvalidator.com:26656,89e8c6097c1cc56e2f1e0f96ef2eedd3dd31aa8c@34.67.180.86:26656,69e8b793059b813d79e5c3f4c4ff9f0d0c7d82e8@216.153.60.190:26656,f1818c94e9fdf77027196f96fe9062002d588c2a@216.153.60.189:26656,2ab5d7d58ed4402ed59ac4731885b7b467ed5cc8@34.102.80.97:26656,2d4f9e5631534ab4cbae88c104784e3148bd8914@88.198.78.120:29103,157c118f01fe869a2a288c0af5911da32284a981@176.9.62.180:57756,ea87b9870ece4d16d302e6162309010d5c4722b3@155.138.194.35:26656,95756e993d96c682f73df79ae68784b142f7cb02@142.132.199.211:27656,15d8ae2a5bc80485b5bde6056f98eaf9b0ba1cf4@142.132.147.125:26656
```

You can also download nightly address book by

```bash
curl https://network.terra.dev/addrbook.json > ~/.terra/config/addrbook.json
```

## Disclaimer

The foundational software for the Phoenix mainnet, Terra Core, is *highly* experimental software. In these early days, we can expect to have issues, updates, and bugs. The existing tools require advanced technical skills and involve risks which are outside of the control of Terraform Labs or its developers. Any use of this open source Apache 2.0 licensed software is done at your _own risk and on a “AS IS” basis, without warranties or conditions of any kind_. **Please exercise extreme caution!**

# Blockchain Vulnerabilities Reported by VPRLab

BlockScope's source code is available at https://github.com/VPRLab/BlockScope.

**BlockScope: Detecting and Investigating Propagated Vulnerabilities in Forked Blockchain Projects**

https://github.com/VPRLab/BlkVulnReport/blob/main/NDSS23_BlockScope.pdf

NDSS paper link: https://www.ndss-symposium.org/ndss-paper/blockscope-detecting-and-investigating-propagated-vulnerabilities-in-forked-blockchain-projects/

The following is the bib information:

```latex
@INPROCEEDINGS{BLKSCP23,
  AUTHOR = {Xiao Yi and Yuzhou Fang and Daoyuan Wu and Lingxiao Jiang},
  TITLE = {{BlockScope}: Detecting and Investigating Propagated Vulnerabilities in Forked Blockchain Projects},
  BOOKTITLE = {Proc. ISOC NDSS},
  YEAR = {2023},
}
```

## A Summary of Vulnerabilities Found in the BlockScope NDSS'23 Paper.

We used this anonymous link, https://tinyurl.com/block-scope, when we submitted the paper.

|Source          |Description                                   |Project     |Fix Status|Clone Type|Patch Commit|VulnType|
|----------------|----------------------------------------------|------------|----------|----------|------------|--------|
|CVE-2022-29177  |Possible Dos Attack                           |Binance     |Accepted  |3         |870b4505    |Forked  |
|CVE-2022-29177  |Possible Dos Attack                           |Optimism    |Pending   |1         |870b4505    |Forked  |
|CVE-2021-41173  |Unexpected Crash                              |Celo        |ACK       |1         |3a6fe69f    |Forked  |
|CVE-2021-3401   |GUI URI Injection                             |DigiByte    |Pending   |2         |a2714a5c    |Fetched |
|CVE-2021-3401   |GUI URI Injection                             |Dash        |Fixed     |1         |a2714a5c    |Forked  |
|CVE-2021-3401   |GUI URI Injection                             |Ravencoin   |Fixed     |3         |a2714a5c    |Forked  |
|CVE-2021-3401   |GUI URI Injection                             |Bitcoin Gold|Pending   |1         |a2714a5c    |Forked  |
|CVE-2021-3401   |GUI URI Injection                             |Dogecoin    |Fixed     |3         |a2714a5c    |Fetched |
|CVE-2020-26265  |Cause chain split (node refuses to accept new)|Optimism    |Pending   |1         |87c0ba92    |Fetched |
|CVE-2020-26264  |Dos Attack                                    |Optimism    |Pending   |1         |bddd103a    |Fetched |
|CVE-2020-26240  |Faulty PoW Calculations                       |Optimism    |Pending   |1         |d990df90    |Fetched |
|CVE-2019-15947  |Wallet Data Leak                              |DigiByte    |Pending   |3         |d8318318    |Fetched |
|CVE-2019-15947  |Wallet Data Leak                              |Litecoin    |Pending   |3         |d8318318    |Fetched |
|CVE-2019-15947  |Wallet Data Leak                              |Dash        |Accepted  |1         |d8318318    |Fetched |
|CVE-2019-15947  |Wallet Data Leak                              |Ravencoin   |Fixed     |1         |d8318318    |Forked  |
|CVE-2019-15947  |Wallet Data Leak                              |Bitcoin Gold|Pending   |1         |d8318318    |Forked  |
|CVE-2019-15947  |Wallet Data Leak                              |Dogecoin    |Fixed     |1         |d8318318    |Fetched |
|CVE-2018-17145  |Potential DDoS Attack                         |Ravencoin   |Fixed     |1         |beef7ec4    |Forked  |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |DigiByte    |Pending   |1         |8313fa8e    |Forked  |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Litecoin    |ACK       |1         |8313fa8e    |Fetched |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Dash        |Accepted  |1         |8313fa8e    |Forked  |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Ravencoin   |Fixed     |3         |8313fa8e    |Forked  |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Horizen     |Pending   |3         |8313fa8e    |Forked  |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Bitcoin Gold|Fixed     |1         |8313fa8e    |Forked  |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Dogecoin    |Fixed     |3         |8313fa8e    |Fetched |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Bitcoin SV  |ACK       |3         |8313fa8e    |Fetched |
|Bitcoin PR#17906|Fix a Race Condition during Qt Test           |Zcash       |ACK       |3         |8313fa8e    |Forked  |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Bitcoin Cash|Pending   |1         |5efcb772    |Forked  |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Dash        |Pending   |1         |5efcb772    |Fetched |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |DigiByte    |Pending   |1         |5efcb772    |Fetched |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Litecoin    |Fixed     |1         |5efcb772    |Fetched |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Ravencoin   |Reject    |1         |5efcb772    |Forked  |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Bitcoin Gold|Pending   |1         |5efcb772    |Fetched |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Dogecoin    |Accepted  |1         |5efcb772    |Fetched |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Zcash       |Reject    |1         |5efcb772    |Fetched |
|Bitcoin PR#16152|Prevent Potential DoS Attack                  |Bitcoin SV  |ACK       |1         |5efcb772    |Forked  |
|Bitcoin PR#15337|Fix Segfault in RPC                           |DigiByte    |Pending   |1         |30d0f7be    |Mixed   |
|Bitcoin PR#15337|Fix Segfault in RPC                           |Bitcoin Gold|Fixed     |1         |30d0f7be    |Mixed   |
|Bitcoin PR#15325|Private Keys could be Imported                |DigiByte    |Pending   |3         |e6c58d3b    |Mixed   |
|Bitcoin PR#15325|Private Keys could be Imported                |Bitcoin Gold|Fixed     |3         |e6c58d3b    |Mixed   |
|Bitcoin PR#15323|Fix Potential Race Condition                  |DigiByte    |Pending   |1         |effe81f7    |Fetched |
|Bitcoin PR#15323|Fix Potential Race Condition                  |Litecoin    |ACK       |1         |effe81f7    |Fetched |
|Bitcoin PR#15323|Fix Potential Race Condition                  |Dash        |ACK       |3         |effe81f7    |Forked  |
|Bitcoin PR#15323|Fix Potential Race Condition                  |Ravencoin   |Pending   |3         |effe81f7    |Fetched |
|Bitcoin PR#15323|Fix Potential Race Condition                  |Bitcoin Gold|Fixed     |1         |effe81f7    |Forked  |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Dash        |Accepted  |1         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |DigiByte    |Pending   |1         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Litecoin    |ACK       |1         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Ravencoin   |Fixed     |3         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Bitcoin Gold|Fixed     |1         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Horizen     |Pending   |3         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Dogecoin    |ACK       |3         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Zcash       |ACK       |3         |4433ed0f    |Mixed   |
|Bitcoin PR#15305|Crash if Disconnecting Fail                   |Bitcoin SV  |ACK       |3         |4433ed0f    |Mixed   |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |DigiByte    |Pending   |3         |fa48baf2    |Forked  |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |Dash        |Accepted  |3         |fa48baf2    |Fetched |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |Ravencoin   |ACK       |3         |fa48baf2    |Forked  |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |Dogecoin    |Fixed     |3         |fa48baf2    |Fetched |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |Horizen     |Pending   |3         |fa48baf2    |Forked  |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |Bitcoin SV  |ACK       |3         |fa48baf2    |Forked  |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |Zcash       |ACK       |3         |fa48baf2    |Forked  |
|Bitcoin PR#15039|Prevent leaking nLockTime fingerprint         |Bitcoin Gold|Fixed     |3         |fa48baf2    |Forked  |
|Bitcoin PR#14993|Fix Data Race                                 |DigiByte    |Pending   |1         |6c10037f    |Forked  |
|Bitcoin PR#14993|Fix Data Race                                 |Dash        |ACK       |1         |6c10037f    |Forked  |
|Bitcoin PR#14993|Fix Data Race                                 |Ravencoin   |Fixed     |3         |6c10037f    |Forked  |
|Bitcoin PR#14993|Fix Data Race                                 |Bitcoin Gold|Fixed     |1         |6c10037f    |Forked  |
|Bitcoin PR#14993|Fix Data Race                                 |Horizen     |Pending   |3         |6c10037f    |Forked  |
|Bitcoin PR#14993|Fix Data Race                                 |Dogecoin    |Fixed     |3         |6c10037f    |Fetched |
|Bitcoin PR#14993|Fix Data Race                                 |Zcash       |ACK       |3         |6c10037f    |Forked  |
|Bitcoin PR#14993|Fix Data Race                                 |Bitcoin SV  |ACK       |3         |6c10037f    |Forked  |
|Bitcoin PR#14897|Prevent Two Particular Attacks                |Horizen     |Pending   |2         |1cff3d6c    |Forked  |
|Bitcoin PR#14897|Prevent Two Particular Attacks                |Zcash       |Pending   |2         |1cff3d6c    |Forked  |
|Bitcoin PR#14897|Prevent Two Particular Attacks                |DigiByte    |Pending   |1         |1cff3d6c    |Forked  |
|Bitcoin PR#14897|Prevent Two Particular Attacks                |Litecoin    |Fixed     |1         |1cff3d6c    |Forked  |
|Bitcoin PR#14897|Prevent Two Particular Attacks                |Ravencoin   |Accepted  |1         |1cff3d6c    |Forked  |
|Bitcoin PR#14897|Prevent Two Particular Attacks                |Dogecoin    |Fixed     |3         |1cff3d6c    |Forked  |
|Bitcoin PR#14897|Prevent Two Particular Attacks                |Bitcoin Gold|ACK       |1         |1cff3d6c    |Forked  |
|Bitcoin PR#14728|Fix Uninitialized Read                        |Ravencoin   |Fixed     |1         |b7b36de     |Forked  |
|Bitcoin PR#14728|Fix Uninitialized Read                        |Dogecoin    |Fixed     |1         |b7b36de     |Fetched |
|Bitcoin PR#13907|Introduce Maximum size for Locators           |Ravencoin   |Fixed     |1         |e254ff5d    |Mixed   |
|Bitcoin PR#13907|Introduce Maximum size for Locators           |Horizen     |Pending   |2         |e254ff5d    |Mixed   |
|Bitcoin PR#13907|Introduce Maximum size for Locators           |Dogecoin    |Fixed     |1         |e254ff5d    |Mixed   |
|Bitcoin PR#13907|Introduce Maximum size for Locators           |Bitcoin SV  |ACK       |3         |e254ff5d    |Mixed   |
|Bitcoin PR#13907|Introduce Maximum size for Locators           |Zcash       |ACK       |2         |e254ff5d    |Mixed   |
|Bitcoin PR#13808|Shuffle Coins for Privacy Protection          |Dash        |Accepted  |1         |18f690ec    |Mixed   |
|Bitcoin PR#13808|Shuffle Coins for Privacy Protection          |Dogecoin    |ACK       |3         |18f690ec    |Mixed   |
|Bitcoin PR#13808|Shuffle Coins for Privacy Protection          |Ravencoin   |ACK       |3         |18f690ec    |Mixed   |
|Bitcoin PR#13808|Shuffle Coins for Privacy Protection          |Horizen     |Pending   |3         |18f690ec    |Mixed   |
|Bitcoin PR#13808|Shuffle Coins for Privacy Protection          |Bitcoin SV  |ACK       |3         |18f690ec    |Mixed   |
|Bitcoin PR#13808|Shuffle Coins for Privacy Protection          |Zcash       |ACK       |3         |18f690ec    |Mixed   |
|Bitcoin PR#12699|Shuffle Tx Inputs                             |Dash        |ACK       |3         |2fb9c1e6    |Mixed   |
|Bitcoin PR#12699|Shuffle Tx Inputs                             |Ravencoin   |ACK       |3         |2fb9c1e6    |Mixed   |
|Bitcoin PR#12699|Shuffle Tx Inputs                             |Dogecoin    |Accepted  |3         |2fb9c1e6    |Mixed   |
|Bitcoin PR#12699|Shuffle Tx Inputs                             |Bitcoin SV  |Reject    |3         |2fb9c1e6    |Mixed   |
|Bitcoin PR#12561|Check Block Corruption                        |Dogecoin    |Fixed     |3         |0e7c52dc    |Mixed   |
|Bitcoin PR#12561|Check Block Corruption                        |Ravencoin   |Fixed     |1         |0e7c52dc    |Mixed   |
|Bitcoin PR#12561|Check Block Corruption                        |Horizen     |ACK       |3         |0e7c52dc    |Mixed   |
|Bitcoin PR#12561|Check Block Corruption                        |Bitcoin SV  |Pending   |3         |0e7c52dc    |Mixed   |
|Bitcoin PR#11568|Disconnect Outbound Peers                     |Horizen     |ACK       |3         |37886d5e    |Mixed   |
|Bitcoin PR#11568|Disconnect Outbound Peers                     |Dogecoin    |Accepted  |1         |37886d5e    |Mixed   |
|Bitcoin PR#11568|Disconnect Outbound Peers                     |Zcash       |ACK       |3         |37886d5e    |Mixed   |
|Bitcoin PR#11568|Disconnect Outbound Peers                     |Bitcoin SV  |Reject    |3         |37886d5e    |Mixed   |
|Bitcoin PR#11531|Check Invalid Block                           |Dogecoin    |Fixed     |3         |015a5258    |Mixed   |
|Bitcoin PR#11531|Check Invalid Block                           |Horizen     |ACK       |3         |015a5258    |Mixed   |
|Bitcoin PR#11531|Check Invalid Block                           |Bitcoin SV  |ACK       |3         |015a5258    |Mixed   |
|Bitcoin PR#11531|Check Invalid Block                           |Zcash       |ACK       |3         |015a5258    |Mixed   |
|Bitcoin PR#10345|Timeout Header Sync                           |Horizen     |ACK       |3         |76f74811    |Mixed   |
|Bitcoin PR#10345|Timeout Header Sync                           |Dogecoin    |Fixed     |1         |76f74811    |Mixed   |
|Bitcoin PR#10345|Timeout Header Sync                           |Zcash       |ACK       |3         |76f74811    |Mixed   |
|Bitcoin PR#10345|Timeout Header Sync                           |Bitcoin SV  |Pending   |3         |76f74811    |Mixed   |


# expData

## directory structure

```txt
.
├──APP_data
│   ├──fake_deposite
│   ├──final_data
│   └──raw_data
├── all_data
│   ├── erc_result
│   └── pattern_result
├── open_source_data
│   ├── erc_result
│   └── pattern_result
├── source_code
├── token_bytecode
└── unique_bytecode
```

## Description

* `erc_result`: tokens with different token standard
    - `*_sol` tokens written by solidity;
    - `*_vy` tokens wrriten by vyper.
* `pattern_result`: tokens of 10 patterns.
* `handle_intra-contract`: executing each intra-contract function invocation only once, these tokens will be missed.
* `irrelevant_variables`: contracts with irrelevant variables
* `fake_notification_addr`: tokens with fake notifications.
* `source_code`: source code of contracts.
* `token_bytecode`: runtime bytecode of token contracts.
* `unique_bytecode`: unique runtime bytecodes.
* `fake_deposit_addr_list`：all addresses not unique
* `fake_deposit_addr_opensource_list`：all open source addresses not unique
* `fake_deposit_addr_opensource_unique`：all open source addresses unique
* `fake_deposit_hash_list`：hash list of unique
* `final_data`:the final statistical results of APP
* `raw_data`:the hash of each transaction







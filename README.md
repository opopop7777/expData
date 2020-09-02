# expData

## directory structure

```txt
./
├── all_data
│   ├── erc_result
│   │   ├── erc1155_addr_sol
│   │   ├── erc20_addr_sol
│   │   ├── erc20_addr_vy
│   │   ├── erc721_addr_sol
│   │   └── erc721_addr_vy
│   ├── fake_notification_addr
│   ├── handle_intra-contract
│   ├── irrelevant_variables
│   └── pattern_result
│       ├── NP1_addr_list
│       ├── NP2_addr_list
│       ├── NP3_addr_list
│       ├── NP4_addr_list
│       ├── NP5_addr_list
│       ├── NP6_addr_list
│       ├── P1_addr_list
│       ├── P2_addr_list
│       ├── P3_addr_list
│       └── P4_addr_list
├── open_source_data
│   ├── erc_result
│   │   ├── erc1155_addr_sol
│   │   ├── erc20_addr_sol
│   │   ├── erc20_addr_vy
│   │   ├── erc721_addr_sol
│   │   └── erc721_addr_vy
│   ├── fake_notification_addr
│   ├── handle_intra-contract
│   ├── irrelevant_variables
│   └── pattern_result
│       ├── NP1_addr_list
│       ├── NP2_addr_list
│       ├── NP3_addr_list
│       ├── NP4_addr_list
│       ├── NP5_addr_list
│       ├── NP6_addr_list
│       ├── P1_addr_list
│       ├── P2_addr_list
│       ├── P3_addr_list
│       └── P4_addr_list
├── README.md
```

## Description

* `erc_result`: tokens with different token standard
    - `*_sol` tokens written by solidity;
    - `*_vy` tokens wrriten by vyper.
* `pattern_result`: tokens of 10 patterns.
* `handle_intra-contract`: executing each intra-contract function invocation only once, these tokens will be missed.
* `irrelevant_variables`: contracts with irrelevant variables
* `fake_notification_addr`: tokens with fake notifications.
# Developer Resources

- [Code Contribution Guidelines](https://github.com/ltcsuite/ltcd/tree/master/docs/code_contribution_guidelines.md)

- [JSON-RPC Reference](https://github.com/ltcsuite/ltcd/tree/master/docs/json_rpc_api.md)

  - [RPC Examples](https://github.com/ltcsuite/ltcd/tree/master/docs/json_rpc_api.md#ExampleCode)

- The ltcsuite Litecoin-related Go Packages:
  - [btcrpcclient](https://github.com/ltcsuite/ltcd/tree/master/rpcclient) - Implements a
    robust and easy to use Websocket-enabled Litecoin JSON-RPC client
  - [btcjson](https://github.com/ltcsuite/ltcd/tree/master/btcjson) - Provides an extensive API
    for the underlying JSON-RPC command and return values
  - [wire](https://github.com/ltcsuite/ltcd/tree/master/wire) - Implements the
    Litecoin wire protocol
  - [peer](https://github.com/ltcsuite/ltcd/tree/master/peer) -
    Provides a common base for creating and managing Litecoin network peers.
  - [blockchain](https://github.com/ltcsuite/ltcd/tree/master/blockchain) -
    Implements Litecoin block handling and chain selection rules
  - [blockchain/fullblocktests](https://github.com/ltcsuite/ltcd/tree/master/blockchain/fullblocktests) -
    Provides a set of block tests for testing the consensus validation rules
  - [txscript](https://github.com/ltcsuite/ltcd/tree/master/txscript) -
    Implements the Litecoin transaction scripting language
  - [btcec](https://github.com/ltcsuite/ltcd/tree/master/btcec) - Implements
    support for the elliptic curve cryptographic functions needed for the
    Litecoin scripts
  - [database](https://github.com/ltcsuite/ltcd/tree/master/database) -
    Provides a database interface for the Litecoin block chain
  - [mempool](https://github.com/ltcsuite/ltcd/tree/master/mempool) -
    Package mempool provides a policy-enforced pool of unmined litecoin
    transactions.
  - [ltcutil](https://github.com/ltcsuite/ltcd/ltcutil) - Provides Litecoin-specific
    convenience functions and types
  - [chainhash](https://github.com/ltcsuite/ltcd/tree/master/chaincfg/chainhash) -
    Provides a generic hash type and associated functions that allows the
    specific hash algorithm to be abstracted.
  - [connmgr](https://github.com/ltcsuite/ltcd/tree/master/connmgr) -
    Package connmgr implements a generic Litecoin network connection manager.

# zkVerify

Implementation of a node for the zkVerify Proof Verification Layer. It is based on the [Substrate](https://substrate.io/) framework.

zkVerify is currently in an early testnet stage. The plan for going live on Mainnet will be communicated later. For more information see [zkVerify.io](https://zkverify.io/).

zkVerify client will connect to ZKV Testnet and start syncing blockchain data.

## Send JSON-RPC requests

Example RPC request:

```
curl http://localhost:9944 \
 -X POST \
 -H "Content-Type: application/json" \
 --data '{"method":"system_syncState","params":[true],"id":1,"jsonrpc":"2.0"}'
``` 

More info about running RPC node in [official documentation](https://docs.zkverify.io/tutorials/how_to_run_a_node/run_using_docker/run_new_rpc_node/) zkVerify.

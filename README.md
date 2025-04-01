# Dummy Rollup Deploy

## Local Dev

```
$ docker compose up
```

If you see this error:

```
error acting as staker
err="error advancing stake from node 2 (hash 0xee288c5dcc61206e6868fa7a01da6abaabe22d6c849718a47eb361857b7e8dd8): error generating node action: block validation is still pending"
```

This error is expected when running a newly deployed rollup with no recent activity. It occurs because there are no new nodes to stake on or no new batches have been posted. Simply let the system continue running.

```
Chain Id:3462746
RPC URL: http://18.142.242.208:8547
Create Rollup Transaction:https://sepolia.arbiscan.io/tx/0x9c8aab3ab8ec56a14a4ac206608d3631bff0c140a175dc21398ed84fc4abeaf9
Create Rollup Transaction Hash:0x9c8aab3ab8ec56a14a4ac206608d3631bff0c140a175dc21398ed84fc4abeaf9
```

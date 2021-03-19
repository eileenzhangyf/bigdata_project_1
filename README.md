# Project 1 Solution

## 1.

### k=2,

xS: 1681087399this_is_a_bitcoin_block_of_55442305

n=150

hash value: 005821783a5637db8696d1b38371885a7338335d12f37e47ecaf517ad48ef7f3

time elapsed: 2s

### k=3,

xS: 128937442this_is_a_bitcoin_block_of_55442305

n=900

hash value: 000f308f0877d3f31905640f855760fd47b1f1db95649d014307f59057ceee79

time elapsed: 2s

### k=4,

xS: 847590765this_is_a_bitcoin_block_of_55442305

n=50000

hash value: 00001fd7884a6e34a1505e4ff89a2dee29aa6127f33a3a2a27e0db1d5c670cd8

time elapsed: 2s

### k=5,

xS: 184144290this_is_a_bitcoin_block_of_55442305

n=1000000

hash value: 000000a05d877c7495c8e4c4be0a67edbd9ff1fa48d8d5aec48ab0deda3f02fc

time elapsed: 6s

### k=6,

xS: 750313587this_is_a_bitcoin_block_of_55442305

n=50000000

hash value: 00000091486bc7c08f018c4292bfa39cc79d818c0a40526993ff0d04f2f9a5c6

time elapsed: 87s


## 2.

xS: 1289975368this_is_a_bitcoin_block_of_55442305

n=1000000000

hash value: 00000007e768f4abf53af7f6fe05fc20ab6c7b1d73595adce1bac52263d9d7d7

time elapsed: 3626s

### Cluster's configuration:

standard (1 Master, N workers)

#### Master Node

Machine type: n1-standard-4 (4 vCPU, 15GB memory)

#### Worker Node

Number of worker nodes: 2

Machine type: n1-standard-4 (4 vCPU, 15GB memory)

### How to estimate the number of trials:

For k=6, I successful found xS when n=50000000. Since there is one more '0' when k=7, I first tried n=500000000, which is a 9-digit number. The result was 'did not found.' Then I tried n=1000000000 because it is a 10-digit number. I successfully found a result. 

## 3.








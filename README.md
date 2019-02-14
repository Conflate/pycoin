# pycoin

## Installing

To install just make sure you have Python >= 3.7.
Run `make install`

## Running

To generate an address, run `make`.
It will at the moment generate a new key-pair, and spit out the public key(address) in decimal.

To clean up, run `make clean-keys`.

To run test script, run `make test`

## Current Status

`make test`

```
[~/pycoin]$ make test
pushd ./src/; python3 ./test.py; popd
~/pycoin/src ~/pycoin
Private key: 54978684512742514587148416961378565697476891270039978718240958191759854592038
Public x: 62133444012352344003920395556390493008526308761189127929097055506934305435260
Public y: 63020377824892835202712565634705054116671054292731394869237045743953880672288
Wallet signatures: 
[(62133444012352344003920395556390493008526308761189127929097055506934305435260, 63020377824892835202712565634705054116671054292731394869237045743953880672288, 59709643652005693189302924017101528245267249368156918369632266309295950147913, 32427665466038152375443861201345954850976365318701288800984920950555787172819)]
The new TX hash is: 
96a296d224f285c67bee93c30f8a309157f0daa35dc5b87e410b78630a09cfc7
We will make a block: 92e7a4098fd4c7c64a4d627122d23ba0907e69ab04cd4e23ff34f91affd15785
We will add the tx: c5529ea8f90ce6d67618ddb7771f9b731e056cc4206f922e69a887c0586ef1df
We will now mine it until the first 4 hex digits are 0
The block finished mining at nonce: 441449
The new hash is: 0000b24cc7feef320a4ab37319292acfc15e01095df064b309a4163dc2453a49
Saving keys, keys made for blocks are automatically saved.
```

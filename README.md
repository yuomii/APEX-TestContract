# APEX-Lottery-Contract
### What it does
Pay 100 CPX and guess a number between 1-1000. If you hit the right number you will recieve 100k CPX

### How to invoke
```
contract call -to APLnbcBHWtBa9MXq6rkPB7EjsHxMhBWVPkT -abi Lottery_abi.txt -m getTicket(<your-guess-number>) -gasLimit 300000 -gasPrice 30k -amount 100
```

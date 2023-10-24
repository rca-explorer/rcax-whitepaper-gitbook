---
description: >-
  Any RCAX Classic tokens can be converted to the new RCAX tokens with a 1:1
  ratio, during a time period of 3 months after the fork launches.
---

# Convert Classic to V2

Follow these steps to convert your RCAX Classic tokens into the new RCAX tokens:

1. Go to [https://polygonscan.com/token/0xC99BD85BA824De949cf088375225E3FdCDB6696C#readProxyContract](https://polygonscan.com/token/0xC99BD85BA824De949cf088375225E3FdCDB6696C#readProxyContract)
2. Click on "9. balanceOf", paste your wallet address and click "Read". Save the resulting amount for later.
3. Then go to [https://polygonscan.com/token/0xc99bd85ba824de949cf088375225e3fdcdb6696c#writeProxyContract](https://polygonscan.com/token/0xc99bd85ba824de949cf088375225e3fdcdb6696c#writeProxyContract)
4. Click "Connect to Web3" and connect with your RCAX Classic wallet.
5. lick on "1. approve" and set "0x875f123220024368968d9f1aB1f3F9C2f3fd190d" as the spender, then set amount to the amount you saved earlier. We need this amount again in a later step.
6. Click "Write" and approve the transaction. Then wait for the transaction to confirm (will be a matter of seconds).
7. Go to [https://polygonscan.com/address/0x875f123220024368968d9f1ab1f3f9c2f3fd190d#writeProxyContract](https://polygonscan.com/address/0x875f123220024368968d9f1ab1f3f9c2f3fd190d#writeProxyContract)
8. Click "Connect to Web3" and connect with your RCAX Classic wallet.
9. Click on "4. convertClassicTokens" and set the amount to the amount you saved earlier.
10. Click "Write" and approve the transaction. Then wait for the transaction to confirm (will be a matter of seconds).
11. Done! You will now have the new RCAX tokens instead of RCAX Classic!
12. (Optional) Import the new RCAX token into MetaMask: [https://tinyurl.com/cspz9mm2](https://tinyurl.com/cspz9mm2)

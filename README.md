# BSUCoin
Create Your Own ERC-20 Token


BOWIESTATE01 - 76bb69d09a820d77b50dcee3721530e91f55aa5b3872026cf4b9b51cded2139c (private) -
0x61f09370a032BBEe2F7cEA151cEDCD102e6140f1 (public)
One minor issue, you will need to specific the quantity, name, and symbol in the code. See attached. This example will produce 100,000,000
tokens.

You will need to paste the solidity code found here: http://bit.ly/SolidityBSU (This link is CASE SENTITIVE) into remix.ethereum.org
  Select a new compiler
    0.4.16+commit (the shortest 0.4.16 in length)
  Wait for the compiler to load (at least 5 seconds)
  Paste the provided code (http://bit.ly/SolidityBSU)
  Press start to compile (wait 5 seconds)
  Press the button “Bytecode”
  The bytecode should be copied to your clipboard
Go to https://wallet.pirl.io/
  Click on Contracts
  Click on Deploy Contracts
    Click on Private Key – enter provided private key
    In the Byte Code Textbox, paste the bytecode
    Remix copies too much!
      Go to the start of the textbox
      Remove –
      {
        "linkReferences": {},
        "object": "
          The first character should be a 0-9,a-f
        Add 0x
          Example 606060 -> 0x606060
        Search for the following:
          ",
          "opcodes":
          Delete the “, “opcodes”: and EVERYTHING AFTER
      If you followed the instructions, properly, the Byte Code and Gas Limit should be green
    Press “Sign Transaction”
    Press “Deploy Contract”
    PAUSE – READ THE REMAINDER OF THE INSTRUCTIONS BEFORE PROCEEDING
      Press “Yes, I am sure! Make transaction.”
      When you press the button, you will get a pop-up – but only briefly. You will need to copy and paste – VERY QUICKLY.

    I recommend press “print scn” and paste the results in a word doc – save the file!!!
      This will be at the very bottom of the page in GREEN –
      The contents will say something like “Your TX has been broadcast to the network.
      This does not mean it has been mined & sent. During times of extreme volume, it may take 3+ hours to send. 
        1) Check your TX below. 
        2) If it is pending for hours or disappears, use the Check TX Status Page to replace. 
        3) Use ETH Gas Station to see what gas price is optimal. 
        4) Save your TX Hash in case you need it later:
            0xc420c6c132b0f1830af4a73e287c06a8f91bb9c45b4f3f8b877e6fbbca6e1a6a
    View your transaction & Contract Address 0x4e7b1f8563e84a7fbfb6b7b70bb3dc801ff28427”  
    You need the last line!
    Now, you are ready – go back to the pause – remember you will only have about 3 seconds to capture this

Yay! – Token Created!
    Use https://www.myetherwallet.com/#view-wallet-info – Point it towards PIRL (top right)
    Enter Private Key
    Lower Right Hand – “Add Custom Token” Button – Press it
      Add Token Contract Address
      Add Token Symbol
      Add Decimals – 3

  Press Save You must have all three correct for the Save to work!

You should see your token 

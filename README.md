# XBT_Blk21M_Funcionality
Copy of the Core with Different Genesys Block to test functionality of software.
The 21 Millions of Fake BTC are already used. Just send me your address and I send you satochis.
The goal is to test the functionality without using regular adresses and avoid the need to 
use IF to toggle between the TestNet and the RealNet.

The Blocks are mined every 2 minutes.
This is just a modified version bitcoin-0.8.6

The Server where you can connect is : 5.135.152.161
Port # are 9725 & 9726

# The Proof of Work:
The stuff I remember changing in the code.

const char* pszTimestamp = "NYTimes - 03/21/2015 Brooklyn Fire Kills 7 Children, City's Worst Toll Since 2007";
assert(block.hashMerkleRoot == uint256("0xf1c73f88796fc7610fba9da6a182ee4be06e8e45b848ecc9c0dce8e2dd1a6cdf"));
block.nTime    = 1296688602;
block.nNonce   = 414098458;

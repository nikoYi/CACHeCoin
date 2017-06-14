Cachecoin official development tree
===================================

Cachecoin is a hybrid Scrypt-Jane-Proof-of-Work, Proof-of-Stake and
Proof-of-Node. It was originally developed by **kalgecin** and taken over
by **vertoe** due to a lack of time to spend on this project by kal. An then 
**kalgecin** restarted the work on cachecoin again after **vertoe** left.

*Note*: The user **kalgecin** on bitcointalk was compromized but he is still
active here on github and has write access to this repository.

* Scrypt-Jane-based coin
* No ASIC miners
* Difficulty adjustment every block.
* Difficulty Adjustment algorithm: Logarithmic
* Block Maturity: 520 Confirms
* Transaction Maturity: 6 Confirmations
* Maximum of ~2 Billion coins per transaction.
* Maximum of 10 mil coin supply
* RPCPort: 2224
* Network Port: 2225


Proof-of-Work
-------------

* Uses Scrypt-Kal Proof-of-Work chacha20/8 (N,1,1) hashing algorithm.
* N increases over time to increase memory requirements.
* 15 minute Proof-of-Work block targets.
* The Proof-of-Work subsidy decreases as difficulty increases.
* Maximum Proof-of-Work reward is 100 coins.


Proof-of-Stake
--------------

* Active Proof-of-Stake mining.
* Coins per annum 10% maximum.
* Coin age to stake: 7 days.



Contact
-------

Here is the current [ANN] https://bitcointalk.org/index.php?topic=1927335.0

Report issues here: https://github.com/kalgecin/cachecoin/issues

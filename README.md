1. Generate a new 32-byte seed for the bls key (we recommend pwgen):

``$ sudo apt install pwgen
$ pwgen -s -y -B 32 1``

If the output has a single-quote symbol ('), rerun until it doesn't.

**NOTE: This is not your Steward or Node seed.**

2. Record the seed somewhere secure.

3. Switch to the indy user.

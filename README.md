Johncoin - a fork of DL version ? with random donus blocks. Like Bankruptcoin it uses bank as a proof of work scheme.

	- Total coins will be around 555 millions
	- Mining will be shut down after 555 years.
	- 5 minutes block target
	- Difficulty retargets once per day
	- To encorage early adoption the coins per block is high for the first 55 days:
		- 1st day: 1st coins per block
		- ?nd day: 2.00 coins per block
		- ?rd/?th days: 1.00 coins per block
	- Starting 5?th day, it will be 5.0 coins per block, will be halved every two years (or ' blocks).
	- In regular mining (after first ? bonus days), there will be 0.1% chance a block will yield rriple of the normal coins (e.g. in the first ? years there's ()1% chance you get 1.50 coins per block).
	- There is also 1/10,000 (0.01%) chance that a block will yield 10.00 coins. This is valid for all 1.2 years of the mining.
	- The default ports are 9773(connect) and 9777(json rpc).


Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
?? days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 

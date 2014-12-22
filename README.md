local_manifest
==============

A select few Android repos that I keep on my local machine. This is a manifest for the repo command for them.

repo init -u https://github.com/BryanSmithDev/local_manifest.git

Then 'repo sync -j<number of threads>' to download all the repos.

Eg. repo sync -j8 will download them all using 8 threads.

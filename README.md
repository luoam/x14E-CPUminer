x14E-CPUminer
=============

x14E-CPUminer for Hcash


my Hshare Address: H76Upr3UwdyLsoRrnFGPcxAUAs1QuLfEFH



Dependencies:
	libcurl			http://curl.haxx.se/libcurl/
	jansson			http://www.digip.org/jansson/
		(jansson is included in-tree)

Basic *nix build instructions:
	./autogen.sh	# only needed if building from git repo
	./nomacro.pl	# only needed if building on Mac OS X or with Clang
	./configure CFLAGS="-O3"
	make

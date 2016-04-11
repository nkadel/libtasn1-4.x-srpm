gnutls-3.4.x-srpm
=================

SRPM building tools for gnutls-3.4.x for runing Samba 4 on RHEL 7
=======

Samba 4.4.x requies gnutls more recent than provided for RHEL 7 or
Fedora 23. This is built from Fedora rawhide releases, and need to be
built, and also requires p11-kit, netttle, and libtasn1 updates

The "make" command will do these steps.

	make build	# Build the package on the local OS
	make all	# Use "mock" to build the packages with the local
			# samba4repo-[os]-x96_64 configuration, provides
			# other needed dependencies
	make install	# Actually install the RPM's in the designated
			# ../samba4repo/[os]/{x8t_64,SRPMS}


		Nico Kadel-Garcia <nkadel@gmail.com>

# Sally - A Tool for Embedding Strings in Vector Spaces
# Copyright (C) 2010 Konrad Rieck (konrad@mlsec.org)

AUTOMAKE_OPTIONS = foreign
SUBDIRS = src doc tests contrib .
ACLOCAL_AMFLAGS = -I m4
EXTRA_DIST = README.md COPYING CHANGES sally.png

clean-local:
	rm -f *~
	rm -f CHANGES

CHANGES:
	$(srcdir)/git2changes.py	        

	

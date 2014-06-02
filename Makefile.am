SUBDIRS = src tests

man/patchelfmod.1.gz:
	gzip -9fk man/patchelfmod.1

man1_MANS = man/patchelfmod.1.gz

doc_DATA = AUTHORS BUGS README.md

strip: all
	$(STRIP) src/patchelfmod

test: check

CLEANFILES = man/patchelfmod.1.gz

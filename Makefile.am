SUBDIRS = src
ACLOCAL_AMFLAGS = -I m4

.PHONY: integration_test

integration_test:
	make -C tests
	tox -e test
	tox -e test_jvm

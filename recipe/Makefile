# Aliases for maintaining this conda package

.PHONY: build install convert upload

VERSION=1.0-0
PACKAGE=mamaba-bash-completion-$(VERSION).tar.bz2

build:
	mamba build . --no-anaconda-upload -c conda-forge

install:
	mamba install -c local --yes --force-reinstall conda-bash-completion

convert:
	mamba convert -p all -o ~/anaconda3/conda-bld ~/anaconda3/conda-bld/linux-64/$(PACKAGE)

upload:
	anaconda upload --skip-existing ~/anaconda3/conda-bld/*/$(PACKAGE)

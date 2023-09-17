# Hunspell binary for Windows 64-bit

[![Build](https://github.com/iquiw/hunspell-binary/actions/workflows/build.yml/badge.svg)](https://github.com/iquiw/hunspell-binary/actions/workflows/build.yml)

This repository sets up GitHub Action for Hunspell build, which builds https://github.com/hunspell/hunspell

See https://github.com/hunspell/hunspell#usage for usage.
Sample dictionary download for Windows using Windows 10 built in curl command (rather than wget in linked usage page):

    curl -o en_US.dic https://cgit.freedesktop.org/libreoffice/dictionaries/plain/en/en_US.dic?id=a4473e06b56bfe35187e302754f6baaa8d75e54f
    curl -o en_US.aff https://cgit.freedesktop.org/libreoffice/dictionaries/plain/en/en_US.aff?id=a4473e06b56bfe35187e302754f6baaa8d75e54f

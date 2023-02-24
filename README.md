# man Template

A template for man files

To turn the groff file to one you would find in any normal packaged program (like python3) do
```bash
groff -man -Tascii programName.1 > programName.1.txt

install -D -m 644 programName.1.txt programName_$(VERSION)_all/usr/share/man/man1/programName.1.gz
```

and replace programName with whatever you program is

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) 


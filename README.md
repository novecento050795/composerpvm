# Composer with php version manager

## Installation
1. wget -O composerpvm.tar.gz https://github.com/novecento050795/composerpvm/archive/refs/tags/1.0.0.tar.gz
2. tar -xf composerpvm.tar.gz
3. mv composerpvm-1.0.0/composerpvm.sh /usr/local/bin/composerpvm
4. rm composerpvm.tar.gz
5. rm -rf composerpvm-1.0.0

## Usage example
```
composerpvm "upgrade vendor-name/package-name" 8.0
```
Where 8.0 is php version

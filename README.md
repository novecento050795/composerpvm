# Composer with php version manager

## Installation
1. ```wget -O composerpvm.tar.gz https://github.com/novecento050795/composerpvm/archive/refs/tags/1.0.1.tar.gz```
2. ```tar -xf composerpvm.tar.gz```
3. ```mv composerpvm-1.0.1/composerpvm.sh $(which composer)/composerpvm```
4. ```rm composerpvm.tar.gz```
5. ```rm -rf composerpvm-1.0.1```

## Usage example
```
composerpvm "install" 8.0
composerpvm "upgrade vendor-name/package-name" 8.0
```
Where 8.0 is php version

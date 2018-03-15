# SQL Operations Studio (preview) is a free tool that runs on Windows, macOS, 
# and Linux, for managing SQL Server, Azure SQL Database, and Azure SQL Data 
# Warehouse; wherever they're running. For more information go to
# aka.ms/sqlopsstudio or https://github.com/Microsoft/sqlopsstudio

# Maintainer: Eric Kang <erickang7@live.com>

pkgname=sqlops-linux
pkgver=0.26.7
pkgrel=1
pkgdesc="SQL Operations Studio for Arch Linux."
arch=("x86_64")
url="http://github.com/Microsoft/sqlopsstudio"
license=("https://github.com/Microsoft/sqlopsstudio/blob/master/LICENSE.txt")
install=sqlops.install
depend=('libunwind')
source=("https://github.com/Microsoft/sqlopsstudio/releases/download/0.26.6/$pkgname-$pkgver.tar.gz")
md5sums=("8f82037ad580d31478eebbe56ff44344")

package(){
    install -d "$pkgdir/opt/sqlops-linux-x64"
    cd $srcdir/$pkgname"-x64"
    cp -R * "$pkgdir/opt/sqlops-linux-x64"
}

# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Eric Kang <erickang7@live.com>
pkgname=sqlops-linux
pkgver=0.26.7
pkgrel=1
pkgdesc="SQL Operations Studio offers a modern, keyboard-focused T-SQL coding experience that makes your everyday database development and management tasks easier with built-in features, such as multiple tab windows, a rich T-SQL editor, IntelliSense, keyword completion, code snippets, code navigation, and source control integration (Git). Run on-demand T-SQL queries, view and save results as text, JSON, or Excel. Edit data, organize your favorite database connections, and browse database objects in a familiar object browsing experience."
arch=("x86_64")
url="http://github.com/Microsoft/sqlopsstudio"
license=('MICROSOFT SOURCE-CODE LICENSE')
install=sqlops.install
source=("https://github.com/Microsoft/sqlopsstudio/releases/download/0.26.6/$pkgname-$pkgver.tar.gz")
md5sums=("8f82037ad580d31478eebbe56ff44344")

package(){
    install -d "$pkgdir/opt/sqlops-linux-x64"
    cd $srcdir/$pkgname"-x64"
    cp -R * "$pkgdir/opt/sqlops-linux-x64"
}
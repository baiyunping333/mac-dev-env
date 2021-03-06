---
priority: 1.0
---

A detailed guide with instructions to compile various software packages to build a web development environment in [OS X 10.10 Yosemite](https://en.wikipedia.org/wiki/OS_X_Yosemite). Start with the **Getting Started** section, then proceed with installing your desired packages. Some packages need to be installed in a certain order to satisfy dependencies. Each package lists its dependencies at the top of its respective page. Archives for previous versions of OS X can be found at the end of this page.

### Getting Started

- [Command Line Tools](/started-cli/)
- [Create the Folder Structure](/started-folders/)

### Source Code Management

- Git
	- [Autoconf](/autoconf/)
	- [Git](/git/)

### Data Stores

- MySQL
	- [CMake](/cmake/)
	- [MySQL](/mysql/)
- [PostgreSQL](/postgresql/)
- [MongoDB](/mongodb/)
- [SQLite](/sqlite/)
- Memcached
	- [Libevent](/libevent/)
	- [Memcached](/memcached/)
- [Redis](/redis/)

### PHP served by Apache
- Apache
	- [PCRE](/pcre/)
	- [Apache](/apache/)
- PHP
	- [LibJPEG](/libjpeg/)
	- [LibPNG](/libpng/)
	- [LibMCrypt](/libmcrypt/)
	- [FreeType](/freetype/)
	- [PHP](/php/)
		- [Autoconf](/autoconf/)
		- [Xdebug](/php-xdebug/)
		- [MySQL for PHP](/php-mysql/)
		- [PostgreSQL for PHP](/php-postgresql/)
		- [MongoDB for PHP](/php-mongodb/)
		- [SQLite for PHP](/php-sqlite/)

### Ruby served by Pow

- Ruby
	- [rbenv](/ruby-rbenv/)
		- [rbenv-gem-rehash](/ruby-rbenv-gem-rehash/)
	- Ruby 2.1.x
		- [OpenSSL](/openssl/)
		- [Ruby](/ruby-21/)
	- Ruby 2.2.x
		- [OpenSSL](/openssl/)
		- [Ruby](/ruby-22/)
	- Gems
		- [RubyGems](/ruby-gems/)
		- [Bundler](/ruby-bundler/)
		- [Ruby on Rails](/ruby-rails/)
		- [MySQL for Ruby](/ruby-mysql/)
		- [PostgreSQL for Ruby](/ruby-postgresql/)
		- [MongoDB for Ruby](/ruby-mongodb/)
		- [SQLite for Ruby](/ruby-sqlite/)
- [Pow](/pow/)

### Node.js

- [Node.js](/nodejs/)
	- [Grunt](/nodejs-grunt/)
	- [Bower](/nodejs-bower/)

### Image Processing

- GraphicsMagick
	- [LibJPEG](/libjpeg/)
	- [LibPNG](/libpng/)
	- [LibTIFF](/libtiff/)
	- [GraphicsMagick](/graphicsmagick/)

---

**Warning:** These instructions are for creating a development environment and therefore security is not considered. For a production system, please refer to each product's respective documentation on how to properly secure each service.

---

If you are attempting to compile a web development environment in a previous version of OS X, check out past versions of the guide:

- [OS X 10.9 Mavericks](http://archives.patrickbougie.com/mac-dev-env/10.9-mavericks/)
- [OS X 10.8 Mountain Lion](http://archives.patrickbougie.com/mac-dev-env/10.8-mountain-lion/)
- [OS X 10.7 Lion](http://archives.patrickbougie.com/mac-dev-env/10.7-lion/)

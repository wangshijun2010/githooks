gitqatools
=========

Git Repostiroy Quality Assurance Tools

Installation
------------
* jshint command line https://github.com/jshint/jshint
    npm install -g jshint
* csshint command line https://github.com/stubbornella/csslint
    npm install -g csshint
* php code sniffer https://github.com/squizlabs/php_codesniffer
    composer install
* php lint wget http://www.icosaedro.it/phplint/phplint-pure-c-1.1_20120402.tar.gz

Usage
-------------

``
git clone https://github.com/wangshijun/githooks
``

Under your git repo root, make symbol link

``
ln -sf /path/to/githooks-repo/hooks/pre-commit.php .git/hooks/pre-commit
``

Configuration
-------------

``
.jshintrc
.csshintrc
``

adam
====

First Project based on FuelPHP


already done

install oil
`$ curl get.fuelphp.com/oil | sh`

`$ cd /path/to/project`

`$ oil create <<PROJECT>>`

`$ cd <<PROJECT>>`

`$ rm -rf .git .gitmodules *.md docs fuel/core fuel/packages`

`$ git init`

    $ git submodule add git://github.com/fuel/docs.git docs
    $ git submodule add git://github.com/fuel/core.git fuel/core
    $ git submodule add git://github.com/fuel/auth.git fuel/packages/auth
    $ git submodule add git://github.com/fuel/email.git fuel/packages/email
    $ git submodule add git://github.com/fuel/oil.git fuel/packages/oil
    $ git submodule add git://github.com/fuel/orm.git fuel/packages/orm
    $ git submodule add git://github.com/fuel/parser.git fuel/packages/parser

`$ git submodule foreach 'git checkout 1.7/master' # バージョンを指定する場合はこっち`

    $ git add .
    $ git commit -m "first commit"
    $ git remote add origin git@github.com:hagimi/adam
    $ git push origin master
    
    
    
How to clone

`$ git clone --recursive git@github.com:hagimi/adam`

or

    git clone git@github.com:hagimi/adam
    git submodule init
    git submodule update

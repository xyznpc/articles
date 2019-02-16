# Python Notes
## Install
* Mac OSX
  - `brew install python` will install python3
  - `brew link/unlink python` 
  - `brew info python`
  - python3 will be `/usr/local/bin/python3`, python will be python2, because some application in OSX may depend on python2
  - [How to set Python's default version to 3.x on OS X?](https://stackoverflow.com/questions/18425379/how-to-set-pythons-default-version-to-3-x-on-os-x/18425592)
* virtualenv
  - `pip install virtualenv`
  - `cd projectDir` && `virtualenv venv`  && `source venv/bin/activate`
  - `pip install <package>` under venv
  - `deactivate`
  
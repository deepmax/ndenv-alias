ndenv-alias
===========

ndenv-alias is a [ndenv](https://github.com/riywo/ndenv) and [node-build](https://github.com/riywo/node-build) plugin which allows you to specify a 'version name alias' when installing node.js/io.js.

Out of the box, ndenv(node-build) does not allow you to install multiple copies of the same
node.js/io.js version. This can be limiting in situations where you want to have
different instances of node.js/io.js with.


Note: This project is a node.js version of [pyenv-alias](https://github.com/s1341/pyenv-alias).


## Installation

```
git clone https://github.com/deepmax/ndenv-alias.git $(ndenv root)/plugins/ndenv-alias
```

## Usage

Specify the version alias name using the `VERSION_ALIAS` environment variable
when performing a `ndenv install`

For example, building a version of node.js 6.5.0:

```
VERSION_ALIAS="my_nodejs" ndenv install v6.5.0
```

autotools_boost_template
============

This package is an GNU Autotools starter template project. It is a starting
point for a C++ project using the Unit Test framework of the famous Boost
library.


## ENVIRONMENT

Tested under:
* Mac OS Sierra
* Xcode 8.2.1
* Homebrew 1.1.6
	* autoconf: stable 2.69 (bottled)
	* autoconf-archive: stable 2016.09.16 (bottled)
	* automake: stable 1.15 (bottled)
	* boost: stable 1.63.0 (bottled), HEAD
	* gcc: stable 6.3.0 (bottled), HEAD
	* pkg-config: stable 0.29.1 (bottled)


## HOWTO

To build this program, start from the root folder:
```shell
  ./bootstrap
  ./configure
  make
```


## RUNNING

After compiling, run test program:
```shell
  $ ./test/test
  Running 1 test case...

  *** No errors detected
```


## LICENSE

Copyright 2017 Rick Lan

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

		http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Introduction

This is a library for Git written in Node.js. It's as close a port of grit http://github.com/mojombo/grit.

The idea is to allow for manipulation of git repositories by the node.js application. Not everything is
implemented directly in node-git. Some of the stuff is using the native git command line instead of
direct javascript code. Also it's fairly synchronous right now but that will hopefully change a little
by little over time as it gets more stable and I start using it in real life scenarios.

The aim of this fork:
- Modernize this library: update all classes so they are ES6, use promises instead of callbacks, and ideally remove sync calls.
- Add documentation via jsdoc

## Github information

The source code is available at http://github.com/douile/node-git.

## Examples

For simple examples of usage look at the tests included in the repository.

## Notes

The current version is basic git support, don't expect everything to work as you expect it
off the bat.

## License

	Copyright 2009 - 2010 Christian Amor Kvalheim.

	  Licensed under the Apache License, Version 2.0 (the "License");
	  you may not use this file except in compliance with the License.
	  You may obtain a copy of the License at

	      http://www.apache.org/licenses/LICENSE-2.0

	  Unless required by applicable law or agreed to in writing, software
	  distributed under the License is distributed on an "AS IS" BASIS,
	  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	  See the License for the specific language governing permissions and
	  limitations under the License.

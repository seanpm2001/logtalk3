________________________________________________________________________

This file is part of Logtalk <https://logtalk.org/>  
Copyright 1998-2021 Paulo Moura <pmoura@logtalk.org>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
________________________________________________________________________


``options``
===========

This library provides useful predicates for managing developer tool and
application options.

API documentation
-----------------

Open the [../../docs/library_index.html#options](../../docs/library_index.html#options)
file in a web browser.

Loading
-------

To load all entities in this library, load the `loader.lgt` utility file:

	| ?- logtalk_load(options(loader)).

Testing
-------

To test this library predicates, load the `tester.lgt` file:

	| ?- logtalk_load(options(tester)).

Usage
-----

The ``options`` category is usually imported by the root object of the
developer tool or application.
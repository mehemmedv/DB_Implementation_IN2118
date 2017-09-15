# DBLite
Database Systems on Modern CPU Architectures


Description
-----------
This is a tiny database systems built from scratch which can do simple select and insert queries.
This is a continuation of the project that I implemented along with Toghrul during the course (https://github.com/togrulseyid/DBLite.git)
In the project during the course, we have implemented Iterator Model for Operators. Here I will continue the project with 'push-up' model implementation and at the end we can simply run queries.


## Development
### Setup repository
```
git clone https://github.com/mehemmedv/DB_Implementation_IN2118.git
```

### Compiling
```
mkdir build && cd build && cmake .. && make
```

Artifacts
---------
* DB - the main service
* DB_Esort -  External sort
* DB_Buffer - Buffer Manager
* DB_SPSegment - Slotted Page
* DB_SCHEMA - Schema(args: test.sql file)
* DB_BTREE - B Tree implementation
* DB_Operators - Operators
* Subscript - cd src/subscript_llvm && make && ./subscript 1 2 5 2
* Parallel Hash Join - cd test && make && ./hashjoin 3000 3000 4


### C++ Programming Style Guidelines
check C++ style guidelines ([Programming Style Guidelines](http://geosoft.no/development/cppstyle.html)) before starting to development 

License
-------

Released under the GNU General Public License v3.0 or later.
See [LICENSE](LICENSE) for further info.

    DBLite
    Copyright (C) 2017 Team: 
        mahammad.valiyev@tum.de

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


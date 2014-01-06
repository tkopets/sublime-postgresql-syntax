Sublime Text PostgreSQL Syntax Definition
=========================================

### Installation

With [Package Control](http://wbond.net/sublime_packages/package_control):

1. Run `Package Control: Install Package` command, find and install `PostgreSQL Syntax Highlighting` plugin.
2. Restart Sublime Text editor (if required)

Using Package Control ensures package will stay up to date automatically.

Manually:

1. Clone or [download](https://github.com/tkopets/sublime-postgresql-syntax/archive/master.zip)
git repo into your packages folder (in Sublime Text, find `Browse Packages...`
menu item to open this folder)
2. Restart Sublime Text editor (if required)


### Usage

Open file with PostgreSQL commands and change syntax to `SQL (PostgreSQL)`.

To open all `*.sql` files using this syntax as default do the following.

1. Open `User` folder of Sublime Text (in Sublime Text, find `Browse Packages...`
menu item to open parent folder).
2. Create a file `PostgreSQL.sublime-settings` with the following contents:

```json
{
    // change default syntax highlight for *.sql files
    "extensions": [ "sql" ]
}
```


### Contributing

See the [TextMate online manual](http://manual.macromates.com/en/) if you are new
to bundle development.

This project uses a BSD compatible license. See the License section for details.


### Credits

John DeSoi, Ph.D.  
Taras Kopets


### License

Copyright © 2010-2011 by John DeSoi, Ph.D.
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name pgEdit nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

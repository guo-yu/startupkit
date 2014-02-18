## startupkit ![npm](https://badge.fury.io/js/startupkit.png)

the startup portal connecting people and workflows

### Installation

```
$ npm install startupkit
```

### Example
run your startup portal on port 8888
````javascript
var startupkit = require('startupkit');

startupkit.run(8888);
````
then open portal in your browser `http://localhost:8888`

### Workflows

startupkit includes many workflows which using the same auth-center and database. It can be merged with local user database too. each workflow provide a web interface, it's designed to be user-friendly, make day-job stuff working ASAP, and it's going to be mobile too.

open your portal and expore those services that built-in:

- Mail Service `/mail`
- Auth Service `/auth`
- Logging Platform `/log`
- Feedback Interface `/feedback`

### startupkit-mail

to be completed

### startupkit-auth

to be completed

### startupkit-log

to be completed

### startupkit-feedback

to be completed

### Contributing
- Fork this repo
- Clone your repo
- Install dependencies
- Checkout a feature branch
- Feel free to add your features
- Make sure your features are fully tested
- Open a pull request, and enjoy <3

### MIT license
Copyright (c) 2014 turing &lt;o.u.turing@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the &quot;Software&quot;), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED &quot;AS IS&quot;, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

---
![docor](https://cdn1.iconfinder.com/data/icons/windows8_icons_iconpharm/26/doctor.png)
built upon love by [docor](https://github.com/turingou/docor.git) v0.1.2
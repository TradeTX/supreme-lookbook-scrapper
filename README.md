# Supreme Lookbook Scrapper

Gather's all the lookbook information from Supreme for you.

FW2017 Data can be found [here](https://gist.github.com/dzt/783b5245318f42951c4ecb7eb19ee5aa) or if you look Google Spreedsheets you can click [here](https://docs.google.com/spreadsheets/d/1viWHstVZWz0jD7z4T-I64g-Tgb0e-3y9w80YpNzAkYQ/edit?usp=sharing).

### Installation/Setup

supreme-lookbook-scrapper requires [Node.js](http://nodejs.org/).

[2018 F/W Export](https://docs.google.com/spreadsheets/d/1LoGrEnzzohWJZ4QJ90mOSss7bwuZiqo6asNf-blgVrg/edit?usp=sharing)

Setup:

```sh
$ git clone https://github.com/dzt/supreme-lookbook-scrapper.git
$ cd supreme-lookbook-scrapper
$ npm install
$ npm start
```

### Can this thing Tweet?

Fosho homie! Just look at the first lines of code in the `index.js` file and set the `twitter` variable as `true` and add your API keys and stuff.

### Where is the CSV file?

When you run the script it will create a file called `results.csv` in the working directory of the script.

### Who

Written by <a href="http://petersoboyejo.com/">@dzt</a>, made better by you.


## License

```
The MIT License (MIT)

Copyright (c) 2017 Peter Soboyejo <http://petersoboyejo.com/>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

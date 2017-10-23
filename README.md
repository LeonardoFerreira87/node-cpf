CPF
===

Funções utilitárias para tratamento de CPF.

Installation
------------

```bash
npm install node-cpf --save
```

---------------------------------------

Examples
--------

* [CPF Validation](#cpf-validation)
* [CPF Mask](#cpf-mask)
* [CPF UnMask](#cpf-unmask)

Cpf Validation
--------------

```js
const cpf = require('node-cpf');

cpf.validate('226.088.422-91'); // returns TRUE
cpf.validate('22608842291');    // returns TRUE

cpf.validate('11111111111'); // returns FALSE

```

Cpf Mask
--------

```js
const cpf = require('node-cpf');

cpf.mask('22608842291'); // returns '226.088.422-91'

```

Cpf UnMask
--------

```js
const cpf = require('node-cpf');

cpf.unMask('226.088.422-91'); // returns '22608842291'

```

---------------------------------------

How to Contribute
-----------------

* Open a pull request or an issue about what you want to implement / change. We're glad for any help!
* Please be aware that we'll only accept fully tested code.

Contributors
------------

 * **Leonardo Thibes <leonardothibes@gmail.com>**

LICENSE
=======

Copyright (c) 2017 Leonardo Thibes

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
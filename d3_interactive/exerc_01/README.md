# Taxa de desemprego nos EUA em agosto de 2016 (Parte 2)

https://observablehq.com/@silviorma/taxa-de-desemprego-nos-eua-em-agosto-de-2016-parte-2@93

View this notebook in your browser by running a web server in this folder. For
example:

~~~sh
python -m SimpleHTTPServer
~~~

Or, use the [Observable Runtime](https://github.com/observablehq/runtime) to
import this module directly into your application. To npm install:

~~~sh
npm install @observablehq/runtime@4
npm install https://api.observablehq.com/d/edf63a8825759310.tgz?v=3
~~~

Then, import your notebook and the runtime as:

~~~js
import {Runtime, Inspector} from "@observablehq/runtime";
import define from "@silviorma/taxa-de-desemprego-nos-eua-em-agosto-de-2016-parte-2";
~~~

To log the value of the cell named “foo”:

~~~js
const runtime = new Runtime();
const main = runtime.module(define);
main.value("foo").then(value => console.log(value));
~~~

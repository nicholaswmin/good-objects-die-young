# good-objects-die-young

Collection of PDF's and running examples on [V8][v8]'s [Generational/Ephemeral Garbage Collection][ggc]

This project focuses on Google's Blink/[V8][v8]'s Garbage Collector (internally called [Oilpan][oilpan]).

Oilpan is a Generational Garbage Collector, so it's recommended to understand the following before continuing:

> Generational Hypothesis: Infant mortality or the generational hypothesis is the observation that, in most cases, young objects are much more likely to die than old objects.

from [Henry G. Baker: 'Infant Mortality' and Generational Garbage Collection](Good-Objects-Die-Young.pdf)

The project should then include examples on where V8's GC shines and where it stutters, including Canvas, DOM and general JS examples.

# Authors

Nicholas Kyriakides, [@nicholaswmin][nicholaswmin]

# License

> The MIT License
>
> Copyright 2023 Nicholas Kyriakides
>
> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


[ggc]: https://en.wikipedia.org/wiki/Tracing_garbage_collection#Generational_GC_(ephemeral_GC)
[v8]: https://v8.dev/
[oilpan]: https://www.youtube.com/watch?v=_uxmEyd6uxo
[nicholaswmin]: https://github.com/nicholaswmin

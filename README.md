# fastdriver
Mini utility to make creation of StackDriver groups faster.

Additionally, you need to have a premium subscription with Stack Driver in order to use their REST API. 

*Please note that as of writing, this is code can be assumed to be in non-working condition (given that it's currently untested).*

## Installing
You have two options:

1. via npm `sudo npm install -g fastdriver`

2. clone this repo, `cd` into it, then run `sudo npm install -g .`

## Running
Once installed, you need to write a FastDriver spec file. Once done, you run:

`$ fastdriver create <filename.yaml>`


## Writing FastDriver spec files
Please see [sample.yaml](sample.yaml) for FastDriver spec file options and explanations.

## License
The MIT License (MIT)

Copyright (c) 2015 Ruben Orduz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
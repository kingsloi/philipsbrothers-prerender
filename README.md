Philips Brothers - Prerender Service (prerender.io)
===========================

Pre-render service used to render a Philips Brothers page in a headless browser (Phantom JS 2.5 beta which is needed to render ES6). The prerender service shipped with https://github.com/prerender/prerender uses the latest (yet old PhantomJS, 2.1 I think), but we need the 2.5 beta (as of May 15th 2017).

## Download and replace old PhantomJS dependency
- Download 2.5 beta for Ubuntu from: https://bitbucket.org/ariya/phantomjs/downloads/
- Navigate to `node_modules/phantomjs-prebuilt/lib/phantom/bin`
- Replace `phantomjs` with the one downloaded
- Edit permissions of file to be executable

## Test via
visit `http://67.205.145.225?_escaped_fragment_=`

## License

The MIT License (MIT)

Copyright (c) 2013 Todd Hooper &lt;todd@prerender.io&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

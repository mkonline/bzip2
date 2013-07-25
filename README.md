README for Matthew J. Francis Java BZip2 library
================================================

This is a mavenised version of the bzip2 java library written by Matthew J. Francis

http://code.google.com/p/jbzip2/

13/10/2011 Version 0.9.1

Features
--------
 * A decompressor that is typically 5% to 10% faster than CBZip2InputStream
 * A compressor of broadly comparable speed to CBZip2OutputStream (slightly slower in some cases, rather faster in others)
 * Legible, well factored code suitable for studying how the algorithms of BZip2 work

Usage
-----
 * To compress data, pass it through a BZip2OutputStream
 * To decompress data, pass it through a BZip2InputStream
 * See the source for worked examples of how to compress and decompress data

Tester Wanted
-------------
 * jbzip2 has been tested successfully on a moderately large and diverse body of data, but more is needed. Please help by testing jbzip2 on your own data
 * Testing can be carried out using the RoundTrip utility included in the distribution :
          bash# java -cp jbzip2-0.9.1.jar demo.RoundTrip /path/to/test/data
 * Each ordinary readable file beneath the given path will be compressed into a temporary file, then decompressed (no files will be created or altered in place). If any error is encountered, the test will stop with an exception
 * Reports of success, as well as failure would be most welcome. Feedback can be sent to the author


Copyright (c) 2010-2011 Matthew J. Francis and Contributors of the jbzip2 Project

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

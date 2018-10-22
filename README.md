# ncmdump-python
A python3 version of ncmdump, which converts netease private music format into regular formats like mp3.

Thanks to [anonymous5l/ncmdump](https://github.com/anonymous5l/ncmdump) who gave the descryption algorithm of .ncm file, and [nondanee/ncmdump](https://github.com/nondanee/ncmdump) who provided the structure of python program.

I removed some codes which were intended to provide compatibility between python 2 and 3, and made the code shorter and slightly easier to understand. Especially, an generator is used to build the stream cipher.

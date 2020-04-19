# sparsenet

> 'sparsenet' is  sparse coding algorithm described by Olshausen  and Field in Nature, vol. 381, pp. 607-609. You can find the source code [here](http://www.rctn.org/bruno/sparsenet/).  

## Usage

  You can run `sparsenet.m` directly or compile your  `.mex` file. This copy was tested on win10, Matlab 2017a.

Clone the git and download the `IMAGES.mat` file from Bruno's [homepage](http://www.rctn.org/bruno/sparsenet/).

You can run `sparsenet` directly, and it should be ok.

Or you can the your  `.mex` file. Go to the nrf/subdirectory and type

~~~
mex -v -I./ cgf.c frprmn.c linmin.c brent.c mnbrak.c nrutil.c
~~~

If successful, this could create the file `cgf.mexw64`(for 64-bit machine). Then copy this file to home directory and run `sparsenet`.


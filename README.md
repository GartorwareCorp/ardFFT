# ArduinoFastFFT

This is a fork of https://github.com/dujianyi/ardFFT

ArduinoFastFFT is a readable FFT code with simple comments. Everyone with C knowledge should be able to read it and modify it.

ArduinoFastFFT increases performance of ardFFT by precalculating a 2D array of needed sines and cosines.

## Usage
`calculateFFT(Xr, Xi, re, im, N, 0, 1)`

or 

`calculateFFT2(Xr, Xi, 0, re, im, N, 0, 1)`

where `Xr` and `Xi` store the real and imagine parts of the frequency, and `re` and `im` are the time signal. Usually `im` are set to be zero. `N` is the number of samples.

More information can be found in the comments.

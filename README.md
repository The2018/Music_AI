# Music_AI

In this project, we extract various level of musical features from different representations of music and experiment with ways to visualize those extracted features. We also reverse the algorithm to restore music from its visualization. 

## bytes

We extract data bytes by bytes from audio representation of music. These representation includes wav file and mp3 file. We visualize those data by
* traditional plot of ampltiude vs time
* RBG values and rectangles/squares
* HSL values and rectangles/sqaures and Hilbert curve
* plot of frequency domains after applying Fourier transform

In addition, we also attempt to convert music back from its visualization. We took HSL values visualization of wav data, read the picture pixel by pixel and convert it back to raw audio data in bytes. Then we compare the reconstructed signal with original signal.

## chord 

We extract the main chords from each bar of the music.

## melody

We extract main melody from scores representation or audio representaiton of music. We experiment with Superatism style visualization and spectrogram.

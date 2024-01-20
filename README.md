# Spectrogram 

Live sound spectrogram in JavaScript. It can be configured to change buffer size,  FFT function, colormap, window type, minimum and maximum frequencies, loudness sensibility, scrolling direction, scrolling speed and pause scrolling.

It has the option to display frequencies in linear mode or in Mel scale (logarithmic scale, see https://en.wikipedia.org/wiki/Mel_scale). 


You can easily add new colormaps, for example to add the colormap "PuBu" add

~~~text
<option value="PuBu">Colormap: PuBu</option>
~~~

after line 61 of index.html.

On the upper left corner it displays the instantaneous value of the frequency with the maximum loudness.

The loudness scales in dB units are not calibrated.

## Usage

- Clone the repository
- Open the file index.html with any web browser

## Live Demo

https://ciiec.buap.mx/Spectrogram/

## Credits

- We use the Web Audio API (https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

- The colormaps were taken from https://github.com/timothygebhard/js-colormaps

- It uses the custom FFT function from https://github.com/lvillasen/FFT.js

## License

[MIT](LICENSE)

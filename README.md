# RealTimeBusTracker
Real Time Bus Tracker
# Real Time Bus Tracker


## Description

This project uses data from class to display bus stops from MIT to Harvard.
I added a zoom control to the map.


### Run Tracker
To run the tracker you can download the folder to your computer and load it into the browser. 

## My process

I received data on bus stop locations from MBTA. When the button is clicked, javascript iterates over the locations and displays them on the map.

### Built with

- [MapBox](mapbox.com) - JavaScript library



```js
let map = new mapboxgl.Map({
  container: 'map',
  style: 'mapbox://styles/emday4prez/cl475f05a000015usq1d69d7e',
  center: [-71.104081, 42.365554],
  zoom: 14,
});
```


### Useful resources

- [Mapbox Documentation](https://docs.mapbox.com/)

## License
Copyright 2022 MIT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

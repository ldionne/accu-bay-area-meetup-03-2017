## Metaprogramming in C++14 and beyond

This repository contains my [reveal.js][]-based presentation on metaprogramming
for the March 2017 ACCU Bay Area C++ Meetup.

## Basic usage
Go to https://ldionne.com/accu-bay-area-meetup-03-2017 or open `index.html`
with your browser. The slides are also available as a pdf in `slides.pdf`.

## Advanced usage
From the root of the repository,
```sh
npm install
grunt serve &
```

and then connect to `localhost:8000` to view locally.

## Building the code samples

```sh
(mkdir build && cd build && cmake ..)
cmake --build build install-dependencies
cmake --build build
```

<!-- Links -->
[reveal.js]: https://github.com/hakimel/reveal.js

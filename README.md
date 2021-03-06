# PhpShooter

A shooter game written in PHP:[FFI](https://www.php.net/manual/en/class.ffi.php)/[SDL2](https://www.libsdl.org/)/[FFI SDL Bindings](https://github.com/SerafimArts/ffi-sdl)

<p align="center">
    <img src="doc/phpshooter.gif?raw=true" width="450" alt="Php shooter screenshot">
</p>

## Requirements

- PHP >= 7.4.0
- ext-ffi `(php.ini -> extension=ffi)`
- SDL >= 2.0
- SDL Image >= 2.0
- SDL TTF >= 2.0

## Installation

### SDL2 Library
- Linux
`sudo apt install libsdl2-2.0-0 libsdl2-image-2.0-0 libsdl2-ttf-2.0-0 -y`

- MacOS
`brew install sdl2 sdl2_image sdl2_ttf`

### PHP Dependencies 
`$ composer install`

## Playing
`php main.php`

- Movement by arrows
- Fire by space


# Ruby Fighter

Street fighter in ruby + gosu.

### Getting Started
To start with you will need some libraries to be installed system-wide.

#### OSX
```
$ brew install sdl2 libogg libvorbis
```
#### Linux
```
$ sudo apt-get install build-essential libsdl2-dev \
                    libsdl2-ttf-dev libpango1.0-dev \
                    libgl1-mesa-dev libfreeimage-dev libopenal-dev libsndfile-dev
```

### Play!
```
git clone https://github.com/MadRabbit/ruby-fighter.git
cd ruby-fighter
bundle
./bin/ruby-fighter
```

If you get `bundle: command not found`, run `sudo gem install bundler`.

### Controls

Player 1
* left - a
* right - d
* punch - e
* kick - r

Player 2
* left - k
* right - ;
* punch - p
* kick - l

# Copyright & License

All assets in this repository are properties of Capcom and copyrighted
to Capcom : Street Fighter® ©CAPCOM U.S.A., INC. ALL RIGHTS RESERVED.

All code in this repository is released under the terms of the MIT license.

Copyright (C) 2015 Nikolay Nemshilov.

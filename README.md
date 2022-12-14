# [sanjibsen/texlive-full](http://hub.docker.com/r/sanjibsen/texlive/)

[![Docker Pulls](http://img.shields.io/docker/pulls/sanjibsen/texlive.svg)](http://hub.docker.com/r/sanjibsen/texlive/)
[![Docker Stars](http://img.shields.io/docker/stars/sanjibsen/texlive.svg)](http://hub.docker.com/r/sanjibsen/texlive/)


This is a Docker image containing a [`TeX Live`](http://en.wikipedia.org/wiki/TeX_Live) installation with many required packages and several fonts.
The goal is to provide a full `Tex Live` installation with all tools and fonts required to do stuff.
I did not use `texlive-full`, but tried to emulate it in order to save some space.

Unfortunately, all in all, this makes the container rather big and not very suitable as base image for my other LaTeX-related containers.
Thus, I also have a smaller `Tex Live` installation with fewer fonts and utils, namely [docker-texlive-thin](http://www.github.com/sanjib-sen/texlive-thin).

## Contact

If you have any questions or suggestions, please contact [Sanjib Kumar Sen](mailto:sksenonline@gmail.com)

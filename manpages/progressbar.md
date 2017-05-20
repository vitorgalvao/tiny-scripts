# progressbar(1) - overlay a progress bar on videos and gifs

## SYNOPSIS

`progressbar [options]` <file…>

## DESCRIPTION

Convert a sequence of images or a video file to a gif or video with a progress bar.

Initially built to make short snippets of looping instructionals clearer as to where they start.

## OPTIONS

* `-c, --bar-color` <color>:
Set the bar’s color. Default: `#f12b24`.

* `-s, --bar-height` <number>:
Set the bar’s height as a percent of the total height. Default: `1`.

* `-p, --bar-position` <top|bottom>:
Default: `bottom`.

* `-d, --delay` <number>:
Delay between each frame, in seconds. Ignored when input is a video. Default: `1.5`.

* `-o, --output-file` <file>:
File to output to. Give it a .mov extension to save as a video, or any other to save as gif. Default: `output.gif` in the current directory.

* `-h, --help`:
Show help.

## AUTHORS

Vítor Galvão (vitorgalvao.com)

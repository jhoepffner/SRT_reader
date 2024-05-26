# SRT_reader
A TouchDesigner .tox reading the .srt subtitles files and showing in over movie

In this repository you will find:
- a TD tox, the proper object
- a TD toe showing how to use the tox

## Manual

You need a proper .srt file.<br>
The best way would be to use the great [Subtitler Edit](https://www.nikse.dk/subtitleedit)<br>
With it you can transcibe your audio from many language, translate it, correct it<br>

You can also use daVinci Resolve where there is good tools for subtitles but transcriptionn need the paying licence.

My device doesn't accept non standard .srt file (double empty lines, more than 2 lines in subtitles etc.)<br>
So use Subtitle edit to correct it<br>
For the moment, it is not possible to use markdown in text Top, so doesn't use bold or italic.<br>
Ask to Derivative to implement it!

### Movie page
- play, pause, rewind: command for the movie
- open Movie Param: open the movie file Top parameters
- movie: open the Movie
- srt: open the subtitles
- srtload: parse the srt for use in TD
### Text page
- textcolor: color of text
- size: size of text
- open Test Param: open the text Top parameters
### Render Page
- onOff: activate subtitles
- positionx, positiony: subtitles position
- rayon: corner or background
- margesx, margesy: margin of background
- bgColor: background color
- bgAlpha: background transparency
### Shadow
- level: opacity of shadows
- blur, shadows blur
- posx, posy: shadow position

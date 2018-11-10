# Making a Mixtape

Had an idea - instead of songs uploaded to youtube being either one static picture or a series of static pictures, you could have it look like a mixtape.

* Uploaded a 32 second video of a cassette tape playing; spliced the same video together a few times to keep the loop effect going
  * [https://josh-res.cloudinary.com/video/upload/cassette-tape.mp4](https://josh-res.cloudinary.com/video/upload/cassette-tape.mp4)
* Uploaded the song "Magic" from the hit movie "Xanadu"
  * [https://josh-res.cloudinary.com/video/upload/xanadu-magic.mp3](https://josh-res.cloudinary.com/video/upload/xanadu-magic.mp3)
* Found a nice google font for text overlay to imitate writing the name of the mixtape on the tape itself - appropriately named "permanent marker"
* Made a waveform of the song, used the make\_transparent effect to remove the background, and then overlayed on the cassette video at the bottom \(adjusted the sizing and padding of the cassette tape video to try to match the in-browser player\), allowing folks to find parts of the song they might like \(similar to soundcloud's visualizations of mixes/etc\)
  * [https://josh-res.cloudinary.com/image/upload/xanadu-magic-wave.png](https://josh-res.cloudinary.com/image/upload/xanadu-magic-wave.png)

Here's how far I got in about 10-15 minutes:

[https://josh-res.cloudinary.com/video/upload/c\_pad,w\_1350,h\_720/fl\_splice,l\_video:cassette-tape,so\_0,c\_pad,w\_1350,h\_720/fl\_splice,l\_video:cassette-tape,so\_64,c\_pad,w\_1350,h\_720/fl\_splice,l\_video:cassette-tape,so\_96,c\_pad,w\_1350,h\_720/l\_video:cassette-tape,so\_128/l\_video:xanadu-magic,du\_128,c\_pad,w\_1350,h\_720/l\_text:Permanent%20Marker\_60\_bold:Fall%202018%20Hits%20-%20Milwaukee%20WI,g\_north,y\_25,w\_1200,co\_black/l\_xanadu-magic-wave,w\_1280,g\_south,h\_100,b\_rgb:00000050/cassette-tape.mp4](https://josh-res.cloudinary.com/video/upload/c_pad,w_1350,h_720/fl_splice,l_video:cassette-tape,so_0,c_pad,w_1350,h_720/fl_splice,l_video:cassette-tape,so_64,c_pad,w_1350,h_720/fl_splice,l_video:cassette-tape,so_96,c_pad,w_1350,h_720/l_video:cassette-tape,so_128/l_video:xanadu-magic,du_128,c_pad,w_1350,h_720/l_text:Permanent%20Marker_60_bold:Fall%202018%20Hits%20-%20Milwaukee%20WI,g_north,y_25,w_1200,co_black/l_xanadu-magic-wave,w_1280,g_south,h_100,b_rgb:00000050/cassette-tape.mp4)

Some things to think about:

* With the video file \(or player\) embedded in to the page, you could predictably know how much padding to leave on the video so the progress bar lines up perfectly with the progress of the song
* If I wanted to do this for 1,000 songs, I'd probably create an extremely long loop of the cassette tape video, re-upload, and then just trim that down to whatever the song \(or collection of songs\) total duration is.
* For a mixtape with multiple songs, you could use meta data from the current song itself \(title and artist, for example\), and use that for another text overlay \(or in any way - be creative!\)


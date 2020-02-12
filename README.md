Goal:
Create line posters based on anime tv shows and movies
Technology Required:
FFMPEG, PYTHON
Steps:

Take movie file and take screenshots at intervals
	https://trac.ffmpeg.org/wiki/Create%20a%20thumbnail%20image%20every%20X%20seconds%20of%20the%20video
	
	
	
Use python to find the dominant colors of the image
	https://stackoverflow.com/questions/43111029/how-to-find-the-average-colour-of-an-image-in-python-with-opencv
	
	
	
	
	
Other concerns in process:
	https://www.metafilter.com/142548/The-Colors-of-Motion
	
	
	
	
HOW DOES IT WORK?
	- A bash script runs ffmpeg to export frames from a video file.
	- The frame rate of the exports depends on the length of the video.
	- The bash script then calls a PHP script which extracts the average color from each frame.
	- The results are spit out as a JSON file with the hex values in an array.
	- The front-end runs on backbone, and presents the color data.
	- Navigate the colors in a number of ways, and compare the color to each frame."
	
	
	
	
Future Features
	analyze audio to figure out the peaks of the movie
	
	
	
	
How to use FFMPEG
	https://video.stackexchange.com/questions/20495/how-do-i-set-up-and-use-ffmpeg-in-windows
	
	
	
	
	
Tool to find average color of image
	http://matkl.github.io/average-color/ 
	
	
	
	
Test Movie
	Spiderman Into the Universe
Another Software to Check Out
https://processing.org/




Another Test
	https://www.youtube.com/watch?v=fzQ6gRAEoy0
	Use Youtube-DL to download
		https://github.com/rg3/youtube-dl/blob/master/README.md#readme




More Reading/Tools
	https://github.com/fluent-ffmpeg/node-fluent-ffmpeg
	
	
	
	http://www.omdbapi.com
	
	
	
	https://thecolorsofmotion.com/faq
	
	
	
	https://pillow.readthedocs.io/en/4.0.x/handbook/overview.html
	
	
	
	https://github.com/atduskgreg/opencv-processing 
What are a list of animated series to try?
Figure out how to use AZW and host the website online?

Movie Combos to Try
2019 Animated movies
Miazaki Films


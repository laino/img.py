python img.py [-whcbvn] image
Options:

	-w --width          - width in pixels, if specified without height, the image will be scaled proportionally
	-h --height         - see width
	-c --character      - character to use for foreground
	-b --as-bash-script - output is a bash script
	-v --verbose        - verbose output
	-n --native         - name of the C-file which will be used to replace xterm_to_rgb and rgb_to_xterm by native methods
	--help              - this 
	image               - Any image or gif (output will be animated)

More info and screenshots: http://crunchbanglinux.org/forums/post/239059/

The color conversion methods are lent from the great Fabulous libary (http://lobstertech.com/fabulous.html)
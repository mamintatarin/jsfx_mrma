# jsfx_mrma
My JSFX plugins
# Installation
Go Reaper->Options->Show Reaper resource path in explorer/finder then open the folder "Effects". Then just drop these files here. May be I'll add ReaPack support later.
Also, you need to install two libraries. Cookdsp library (download from here http://ajaxsoundstudio.com/software/cookdsp/ or https://github.com/belangeo/cookdsp) and geraintluff library for GUI (link for ReaPack - https://raw.githubusercontent.com/geraintluff/jsfx-ui-lib/master/ui-lib.jsfx-inc , direct link to code - https://stash.reaper.fm/v/32955/ui-lib.zip)
## (A)GAIN - guitar amplifier
This plugin is a simple waveshaping distortion + some EQ for input and output signals to make it sound like a default metal amp. 
Of course, I took some general ideas from other amplifier plugins.
Please, use it before IR loader, e.g. convolution Cabinet Sim (default Reaper plugin). You can use a compressor between this plugin and cab.
![изображение](https://user-images.githubusercontent.com/42464672/156220663-e1555226-5ad0-46a2-8924-35f57aa3c6ff.png)


### Input gain
This button sets the amount of input gain (before the waveshaper). The input signal is not the same as your sound before the plugin: it goes through some EQ first.
### Output gain
This button sets the amount of output gain (after the waveshaper). Again, it's applied to a waveshaped signal with some fixed EQ + tune EQ that you can control. Be careful with that since there is no hardclipper at the end of the plugin - you should control clipping by looking at the output indicator.
### Tune
Here we have three sliders to control some low, mid and high character. 

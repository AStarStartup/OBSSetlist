OBS Setlist is an OBS filter plugin for chopping up live streams into clips and displaying timeline progress and the current clip title in-stream using a HUD, IMUL Markdown, and the AStartup MCC to upload clips to social media.

To create a Setlist write a list of titles for the sub-videos you want to clip from your stream using IMUL Markdown with one title per line. You add the OBS Setlist filters to scenes in OBS, load the IMUL Markdown text file, and configure which scene is the start and stop of the sub-video. You may use the same end screen to stop all the sub-video clips, or just some of them.

When you enter or exit the scenes you just configured, it will mark the timestamps when the plugin is activated and deactivated. This will be saved as an IMUL Markdown file in the same folder you loaded the IMUL Markdown script from. When you have stopped recording a BASH or Powershell script will be generated that you can run that will chop up the recording into clips with FFMPEG.

Once this is done you will need to load the IMUL Markdown output into the [AStartup MCC browser extension](https://github.com/AStarStartup/AStartupMCC) by right clicking on the AStartup extension icon in the browser and selecting Run IMUL Script. This will pop up a menu that will walk you through the rest of the process of uploading the clips to social media.

Posts for social media can be customized using IMUL scripts, which are like Markdown files with scripts in them and a templating engine similar to Liquid/Jekyll.

## Status

I started this project on 2022-07-22 so this is a virgin greenfield project. I haven't coded in Qt in over 10 years, I'm a C++ master, so I'm taking a Udemy class on Qt 5 that should take a week for me to get through tops. The IMUL compiler has a lot of work to do.

## Roadmap

You can find the project roadmap in the [GitHub Milestones for this repo](https://github.com/AStarStartup/OBSSetlist/milestones).

## License

Copyright ©2022 [AStartup](https://astartup.net); all rights reserved.

# Audio feature extraction workspace

Use the timbreID_Workspace.pd patch to explore audio feature extraction using
the timbreID external and timbreID library for Pure data.

[Pure data](http://puredata.info/downloads/pure-data) Vanilla (Version 0.50-2) and the [timbreID](https://github.com/wbrent/timbreID) external are necessary for this patch to work.

timbreID_Wokspace.pd is documented inside the patch. See the timbreID documentation and help files for further information about this external.

amenbreak.wav is provided as initial audio file loaded by the patch an must be placed in the same directory then the timbreID_Workspace.
Same for tap_tempo_7_TH.pd abstraction, which a version of tap_tempo_7.pd (based on tap.tempo.pd from https://forum.pdpatchrepo.info/user/weightless) that I made for it to work with Pure Data vanilla distributions.

Stereo audio file playback, two channel audio input, three different trigger objects, single- and multi-feature analyzer templates
and a feature-list-builder are ready to use.

timbreID feature lists and cluster lists can be stored and recalled.

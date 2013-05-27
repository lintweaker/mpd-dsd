mpd-dsd
=======

Version of stable MPD 0.17.4 for fasttracking DSD playback development.
Once development is complete the changes / enhancements will be submitted to
MPD.

Planned DSD playback enhancements en fixes:

Enhancedments:
- DSD128 playback with DoP using one stereo channel @ 352.8
- DSD128 playback with DoP using two stereo channels @ 176.4

Fixes:
- MPD hang at the end of a song when playing certain DFF files
- Pops at the end of certain DSF files

Planned enhancements:
- Re-introduce fast forward and rewind for both DSF and DFF files
- Utilize DSD/DoP support provided by ALSA in kernel 3.6.10 and up


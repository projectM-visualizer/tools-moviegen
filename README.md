projectM Quicktime Movie Generator
==================================

This is a small utility project that can be used to turn any Quicktime-supported audio file into a music video, playing
projectM visualizations alongside the audio.

It uses the simple "Mov123" command-line tool to encode the stream and requires the Quicktime SDK to be installed on
either Windows or macOS.

This tool is released under the GNU General Public License 3,0, not LGPL 2.1 as most other projectM code, to stay
compatible with the stricter GPL licensing terms of the code contained in  `mov123.c`.
# BuildCored-Orcas-Day15
AudioScope — BUILDCORED ORCAS Day 15

What it does. It acts like a "prism" for sound, shredding messy audio waves into a clear spectrum so you can see the volume of specific pitches instead of just a single wiggly line. It essentially translates sound from the "time domain" (how it looks on an oscilloscope) to the "frequency domain" (how it looks on an EQ).

Hardware concept. This mimics a Hardware Spectrum Analyzer or a Graphic Equalizer, using filter banks to bucket electrical signals into specific frequency ranges. It’s the same logic found in everything from high-end studio gear to the "Bass Boost" circuit in a car stereo.

Screenshot. https://drive.google.com/file/d/1ADL040cY418jl-DOwcvYS6wvLnJdJJ59/view?usp=sharing

What I would do differently. I would switch to a logarithmic scale for the volume and frequency because that's how human ears actually perceive sound, making the visual movement feel more natural. I’d also add a "peak decay" feature so the bars drop smoothly like professional gear rather than flickering instantly.

Run it. python day15_starter.py

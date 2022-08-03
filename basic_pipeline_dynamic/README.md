# Basic GStreamer Pipeline (dynamic)

This project is a basic gstreamer app. 
A gstreamer pipeline is constructed where source, filter, and the sink elements are linked with each other. Elements are linked with each other over interfaces called pads and the media format that flows through these are exposed through caps. The elements are linked through pads on the fly, this leverages the gstreamer features to construct a fully dynamic and flexible media processing pipeline.
# IRIG Decoder for Arduino

IRIG Decoder for arduino. Currently supports IRIG-B format, but can theoretically work for any format provided pulse lengths are modified within `int pType(unsigned long len)`.

Initial implementation released on 17 Feb 2017. No performance promises can be made about this code as no performance evaluations have been ran on it. Tested to work with IRIG-B Unmodulated output from an Arbiter 1093B satellite controlled clock. Example provided within .ino sketch.

If you have any suggestions, please don't hesitate to open an issue or pull request - all are welcome.

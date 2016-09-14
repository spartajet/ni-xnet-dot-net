# ni-xnet-dot-net
NI-XNET (CAN/LIN/FlexRay) driver .net/C# wrapper

NiXnetDotNet is a C++/CLI wrapper around the National Instruments NI-XNET C driver to allow .net programs (like SeqZap) to use the driver without having to resort to PInvoke.

NI-XNET are advanced CAN/LIN/FlexRay interfaces with integrated processing units so the timing of the bus in question is correct.

The primary use of this wrapper is to allow SeqZap to access NI-XNET devices during system testing, but are releasing this wrapper as open-source to safe other people from having to do the same work to access their NI-XNET interfaces from .net.

NiXnetDotNet is released under an Apache 2.0 license (see License.txt for details).
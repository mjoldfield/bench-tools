# bench-tools

Lots of test gear can be connected to a computer. Historically,
GPIB was used, these days serial, USB and ethernet are common.

On the software side, standards exist. For example,
[VISA](https://en.wikipedia.org/wiki/Virtual_Instrument_Software_Architecture),
[SCPI](https://en.wikipedia.org/wiki/Standard_Commands_for_Programmable_Instruments)
are common.

However, at the end of the day in many cases everything boils down to
exchanging messages in a friendly and well-documented format, so for
*casual use* it might be easier to just write some Perl (or python
if you're that way inclined).



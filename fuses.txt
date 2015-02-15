# TV-B-Gone
### The SMD version

This is a fork of [Adafruit's tv b gone kit](https://github.com/adafruit/TV-B-Gone-kit). I added a lithium charging and protection circuit, and converted the board to be surface mount. It is single-sided and can be made easily on a circuit mill. 

It is tested and works.

## Notes:

avrdude -c avrispmkII -p t85 -B 250 -u -U lfuse:w:0xfd:m -U hfuse:w:0xdf:m

avrdude -c avrispmkII -p t85 -b 19200 -U flash:w:tvbgone.hex:i
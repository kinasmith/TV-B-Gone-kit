avrdude -c avrispmkII -p t85 -B 250 -u -U lfuse:w:0xfd:m -U hfuse:w:0xdf:m

avrdude -c avrispmkII -p t85 -b 19200 -U flash:w:tvbgone.hex:i
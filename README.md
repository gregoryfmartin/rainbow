# Rainbow
24-bit color definitions in Python. This is a derivation from a PowerShell program I wrote called Eldoria which, despite my sincerest efforts, has languished to the point of disrepair. This code was ported to Python to try and keep it alive for my own sake.

The ConsoleColor class serves as the foundation for all specific colors by defining itself as a 24-bit RGB color. Abstractions of this class are intended to be used in ANSI 24-bit SGRs. If this is integrated with other TUI frameworks in Python, like Textual, it's likely that these will either conflict or not work.

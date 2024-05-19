# feather33
Feather form-factor board with a 1.4GHz quad-core A33 from Allwinner.

For assembly, any <=512MB DDR3L should* work (no MCP). 

A 50p board-to-board connector is added to break out another USB, audio, and parallel RGB among other things

This board is designed to work with OSHPark's 6L service and to be assembled with a stencil and hotplate/hot air.

## Initial Testing
Assembled board works fine and communicates over USB.
2 IMPORTANT THINGS!!!
- You cannot boot from MMC1, sadly I discovered this *after* I got the boards. You'll have to first boot off of a SPI flash then use that to jump onto MMC1.
- DDR is still not confirmed.

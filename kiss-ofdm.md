# Protocol

Keep it simple, stupid OFDM protocol.

## Signal structure
 * encode data bits
 * add preamble
 * add pilots
 * no bitloading on DC area, left/right ends of spectrum
 * BPSK modulation
 * 256 subcarriers per symbol
 * IFFT
 * 1/4 Guard Inteval

[kiss-ofdm.grc](kiss-ofdm.grc)

# Protocol

Keep it simple, stupid OFDM protocol.

## Signal structure
 * encode data bits
 * add preamble symbols
 * add 32 pilots
 * zeros in DC area [-7..7]
 * zeros left/right ends of spectrum [-128..-97, 97...127]
 * 128 data subcarriers per symbol
 * BPSK modulation
 * IFFT 256
 * 1/4 Guard Inteval

[kiss-ofdm.grc](kiss-ofdm.grc)

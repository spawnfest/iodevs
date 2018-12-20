Because we didn't know if we can still add another codes to this repo after the deadline, we've been making a decision to move all to our repo at [iodevs](https://github.com/iodevs/qr_code) and then here fluently continue in working... :-)

# QrCode

As surely know, in elixir world exists one, maybe two generators of QR code. One of them is [Sunboshan](https://github.com/sunboshan/qrcode)'s library, but this lib is a little bit limitated. It's working only with version: 1 - 7, ECC level is L and the generated QR code is displayed only on terminal. With this library works also repo [qr-code-svg](https://github.com/ondrej-tucek/qr-code-svg) which generate the QR code to svg file. 

In our case we want to make QR generating for all versions and ECC levels according to [https://www.thonky.com/qr-code-tutorial](https://www.thonky.com/qr-code-tutorial/). See [iodevs/qr_code](https://github.com/iodevs/qr_code)

## Installation

```elixir
def deps do
  [
    {:qr_code, "~> 0.1.0"}
  ]
end
```

## License

> TODO: Add license

----
Created:  2018-11-24Z

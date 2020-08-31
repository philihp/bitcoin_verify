# BitcoinVerify

Package for verifying multi-sig address messages in the format

```
-----BEGIN BITCOIN SIGNED MESSAGE-----
Philihp 2020-08-31
-----BEGIN SIGNATURE-----
33TM5WUnpeZoSeb3XDZFqE86nL7e9LXXoq
HzPPcoFMgDNU/euuJMUUYY6sEv+v+SSpupYeRVuYMsT8Bxxzp41HsN7oL0wssi5+jOCzDUux9zinyBeGy0pfb6A=
-----END BITCOIN SIGNED MESSAGE-----
```

## Usage

```elixir
iex(1)> Bitcoin.Verify.message(seeabove)
# true
iex(2)>
```

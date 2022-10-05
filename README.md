# key-expander

An AES key schedule implementation in Rust.

Only supports 128-bit keys, with 10 rounds of key expansion.

### Example usage:
```rust
let key: Key = [0xf7f7f7f7, 0x31313131, 0x12345678, 0x1];
let round_keys = expand_key(key);
```

### TODO:
 - [ ] Add code docs with examples


### Read more about AES/Key schedules
 - https://en.wikipedia.org/wiki/AES_key_schedule
 - https://en.wikipedia.org/wiki/Advanced_Encryption_Standard
 - https://braincoke.fr/blog/2020/08/the-aes-key-schedule-explained/

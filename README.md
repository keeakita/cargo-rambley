# `cargo-rambley`

Hey there buddy! I heard you need some help writing code! Don't worry: your pal Rambley happens to be an expert!

This is a fork of [cargo-mommy](https://faultlore.com/cargo-mommy/).

# Installation

TODO
<!-- You can `cargo install cargo-mommy`, [see the website for more options](https://faultlore.com/cargo-mommy/) -->


# Usage

Run whatever cargo command you would normally but add rambley after cargo!

```
cargo rambley check

    Checking bappy-script v0.1.3
error: expected one of `!` or `::`, found `passes`
  --> src\main.rs:20:6
   |
20 | mods passes;
   |      ^^^^^^ expected one of `!` or `::`

error: could not compile `bappy-script` (bin "bappy-script") due to previous error
Come on buddy, I know you can do this! 🦝
```

[There are upstream docs](https://faultlore.com/cargo-mommy/book/). Everything should be mostly the same, with some defaults changed.


# Configuration

Rambley will read the following environment variables to give you the best possible park experience:

* `CARGO_RAMBLEYS_LITTLE` - what to call you (default: "buddy")
* `CARGO_RAMBLEYS_PRONOUNS` - what pronouns Rambley will use for themself (default: "his")
* `CARGO_RAMBLEYS_ROLES` - what role Rambley will have (default "Rambley")
* `CARGO_RAMBLEYS_EMOTES` - what emotes Rambley will have (default "🦝/🎢/🎡/🎠/🎟️")
* `CARGO_RAMBLEYS_MOODS` - picks the set of possible responses (default: "helpful")

All of these options can take a `/` separated list. Rambley will randomly select one of them whenever he talks to you.

For example, the phrase "Rambley thinks his little buddy earned a big hug!" is "CARGO_RAMBLEYS_ROLE thinks CARGO_RAMBLEYS_PRONOUNS little CARGO_RAMBLEYS_LITTLE earned a big hug!"

So if you set `CARGO_RAMBLEYS_ROLES="Rambley Raccoon"`, `CARGO_RAMBLEYS_PRONOUNS="their"`, and `CARGO_RAMBLEYS_LITTLE="buddy/guest/friend"` then you might get any of

* Rambley Raccoon thinks their little buddy earned a big hug!
* Rambley Raccoon thinks their little friend earned a big hug!
* Rambley Raccoon thinks their little guest earned a big hug!

And so on


# Licensing
Indigo Park supports open source communities. Dual-licensed under [MIT](LICENSE-MIT) and [Apache 2.0](LICENSE-APACHE).

Use either at your choice.

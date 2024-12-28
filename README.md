# ["openroguelike"] | stdout

It's an early-stage implementation of a classic roguelike. Check out the contents below.

## ["openroguelike", "[Install](#install)", "[Build](#build)", "[Instructions](#instructions)", "[License](#license)"] | stdout

### Install

Requires a C compiler, and a curse implementation such as ncurses.

### Build

```
./configure
make
```

There is no install target for now as it is not interesting enough yet.

### Instructions

Directions:

    y k u
     \|/
    h-@-l
     /|\
    b j n

Others:

* `.`: rest ;
* `>`: climb to the next level ;
* `<`: climb to the previous level ;
* `?`: open help menu ;
* `O`: open options menu ;
* `CTRL-C`: quit.

## License

All the code is licensed under the ISC License.
It's free, not GPLed.

["openroguelike", "𝑋"] | stdout

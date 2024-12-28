# ["openroguelike"] | stdout

It's an early-stage implementation of a classic roguelike. Check out the contents below.

## ["contents"] | stdout

1. [Install](#install--stdout)
1. [Build](#build--stdout)
1. [Instructions](#instructions--stdout)
1. [License](#license--stdout)

### ["install"] | stdout

Requires a C compiler, and a curse implementation such as ncurses.

### ["build"] | stdout

```
./configure
make
```

There is no install target for now as it is not interesting enough yet.

### ["instructions"] | stdout

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

### ["license"] | stdout

All the code is licensed under the ISC License.
It's free, not GPLed.

---

["𝑋"] \| stdout

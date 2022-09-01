# Space Worm Contract
- [`SpaceWorm.sol`](https://github.com/SpaceWormETH/SpaceWorm-contract/blob/master/SpaceWorm.sol)

```
░██████╗██████╗░░█████╗░░█████╗░███████╗  ░██╗░░░░░░░██╗░█████╗░██████╗░███╗░░░███╗
██╔════╝██╔══██╗██╔══██╗██╔══██╗██╔════╝  ░██║░░██╗░░██║██╔══██╗██╔══██╗████╗░████║
╚█████╗░██████╔╝███████║██║░░╚═╝█████╗░░  ░╚██╗████╗██╔╝██║░░██║██████╔╝██╔████╔██║
░╚═══██╗██╔═══╝░██╔══██║██║░░██╗██╔══╝░░  ░░████╔═████║░██║░░██║██╔══██╗██║╚██╔╝██║
██████╔╝██║░░░░░██║░░██║╚█████╔╝███████╗  ░░╚██╔╝░╚██╔╝░╚█████╔╝██║░░██║██║░╚═╝░██║
╚═════╝░╚═╝░░░░░╚═╝░░╚═╝░╚════╝░╚══════╝  ░░░╚═╝░░░╚═╝░░░╚════╝░╚═╝░░╚═╝╚═╝░░░░░╚═╝
```
How it works:
- There are fees in place which are:
  - An `automatic Burn` on every transaction, to create a hyperdeflationary token (rapid drop in Supply, which automatically updates/is removed from existence)
    - `3% Buy` / `4% Sell`
  - A `Marketing Fee` for project longevity
    - `2% Buy` / `3% Sell`
  - A `Liquidity Fee` for project longevity & higher floors
    - `1% Buy` / `1% Sell`
    - Liquidity is injected as only the token, directly into the LP on every transaction (saves fees and swapping)
  - 15%/25% max Buy/Sell tax restriction in functions
  - Can renounce individual functions(/groups of functions) if needed in future: Delay Timer, Fee Functions, Max Update Functions, Market Maker Pair    Changes, Wallet Changes, and Exclude Include Functions
  - 180 Second Sell Delay Timer (wallets cannot sell for 180 seconds after making any transaction). Anti-whale & bot-flip function.

```
                         ___---___
                      .--         --.
                    ./   ()      .-. \.
                   /   o    .   (   )  \
                  / .            '-'    \ I feel so incredibly LIGHT!
                 | ()    .  O         .  | I wonder what's the
                |                         | reason for this anomaly?
                |    o           ()       |
                |       .--.          O   |
                 | .   |    |            |
                  \    `.__.'    o   .  / $WORM
                   \                   /
                    `\  o    ()      /'
                      `--___   ___--'
                            ---
                          ████████
                        ██░░░░░░░░██
                      ██    ░░    ░░██
                    ██░░  ██░░██  ░░██
                    ██░░  ██░░██  ░░██
                    ██░░░░░░░░░░░░░░██
                    ██░░  ░░░░░░  ░░██
                      ██░░      ░░██
                        ██░░░░░░██
                        ██░░░░░░██
                        ██░░░░░░██
                        ██░░░░░░██
                          ██░░░░░░██
                          ██░░░░░░░░██
                            ██░░░░░░░░████████      ██████████
                          ██░░░░░░░░░░░░░░░░░░██████░░░░░░░░░░██
                          ██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░████
                          ██░░░░██████████░░░░░░░░░░████░░░░░░░░░░░░██
                            ████          ██████████    ██████░░░░░░██
                                                              ██████
```
---
```
  }}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}
  {{            +             +                  +   @          {{
  }}   |                *           o     +                .    }}
  {{  -O-    o               .               .          +       {{
  }}   |                    _,.-----.,_         o    |          }}
  {{           +    *    .-'.         .'-.          -O-         {{
  }}      *            .'.-'   .---.   `'.'.         |     *    }}
  {{ .                /_.-'   /     \   .'-.\                   {{
  }}         ' -=*<  |-._.-  |   @   |   '-._|  >*=-    .     + }}
  {{ -- )--           \`-.    \     /    .-'/                   {{
  }}       *     +     `.'.    '---'    .'.'    +       o       }}
  {{                  .  '-._         _.-'  .                   {{
  }}         |               `~~~~~~~`       - --===D       @   }}
  {{   o    -O-      *   .                  *        +          {{
  }}         |                      +         .            +    }}
  {{ $WORM        .     @      o                        *       {{
  }}       o                          *          o           .  }}
  {{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{{
```
```
                                 ___
              _____________ * .'`  _\ $WORM
     ....-''``'._ _________) /  (o/       *
             ,_  '-.___)    |     _\           *
               `'-._)_)      \  '==.    *
     -----'``"-,__(__)    *   '.____\       ~*
```

---

[This Repo is licensed under an MIT LICENSE](./LICENSE)

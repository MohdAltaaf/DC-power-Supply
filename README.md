# DC power Supply

## What this is:
This is my version of making a variable DC power supply to supply my projects a constant voltage that they might need, 3.3V? 5V? It can go from 0 all the way to ~9V. 

## Why was this made?:
Im studying Electronics and communication engineering, so Basic electrical engineering is a part of my curriculum, 
I was just taught about rectification and function filtering. I made this to get practical experience such as soldering, debugging connections , going out to local markets to buy components. 
It was a nice experience and it works as inteded as well!

## How to make it?:
First get all the components mentioned in the BOM : 

| Ref | Part | Value / Rating | Qty | Est. Unit Cost (USD) | Est. Total (USD) |
|-----|------|----------------|-----|---------------------:|-----------------:|
| T1 | Step-down transformer EM-3857-AC230V-1 | 230 V → 9.5 V AC, 1.0 A | 1 | $3.77 | $3.77 |
| SW1 | SPST toggle / rocker switch | 250 V AC, ≥1 A | 1 | $0.43 | $0.43 |
| F1 | Fuse | 250 mA slow-blow, 250 V | 1 | $0.16 | $0.16 |
| D1-D4 | 1N4007 diode | 1 A, 1000 V | 4 | $0.03 | $0.13 |
| C1 | Electrolytic capacitor | 2200 µF / 25 V | 1 | $0.49 | $0.49 |
| C2 | Ceramic capacitor | 0.33 µF (0.1 µF also fine) | 1 | $0.05 | $0.05 |
| U1 | L7805CV regulator (TO-220) | 5 V, 1.5 A | 1 | $0.22 | $0.22 |
| C3 | Ceramic capacitor | 0.1 µF | 1 | $0.05 | $0.05 |
| C4 | Electrolytic capacitor (optional) | 1 µF / 25 V | 1 | $0.05 | $0.05 |
| P1 | Potentiometer | 10 kΩ linear | 1 | $0.22 | $0.22 |
| Output | Terminals / binding posts | Red, green, black | 3 | $0.16 | $0.49 |
| | **Estimated Total** | | | | **$6.06** |

Not very expensive tbf.

Now Follow the circuit diagram provided:
<img width="1315" height="415" alt="image" src="https://github.com/user-attachments/assets/56e88efd-a417-4846-a4be-5a6e820ff1d0" />

Hook up the transformer to the circuit and power it on and it should be good to go!

## Precautions: 
- Since this is going to be plugged it directly to a wall, please ensure there is a fuse before your transformer things might get ugly otherwise.
- Check for any shorted or bridged connections you dont want a 2200uF capacitor blowing up on you. 

### That's Pretty much it!


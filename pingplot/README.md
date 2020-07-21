# pingplot

A quick wrapper over `ping` in [fish](https://fishshell.com/) to show live ping latencies as a horizontal character bar graph

## Usage

`normal` mode
```
♪  ./pingplot 8.8.8.8
8.8.8.8   20.40 (avg)   0 (drop) |||||||||||||||||||| 20.4 ms
8.8.8.8   12.70 (avg)   0 (drop) |||| 4.99 ms
8.8.8.8    9.77 (avg)   0 (drop) ||| 3.92 ms
8.8.8.8   21.68 (avg)   0 (drop) ||||||||||||||||||||||||||||||||||||||||||||||||||||||||| 57.4 ms
8.8.8.8   18.25 (avg)   0 (drop) |||| 4.52 ms
8.8.8.8   19.50 (avg)   0 (drop) ||||||||||||||||||||||||| 25.8 ms
8.8.8.8   17.94 (avg)   0 (drop) |||||||| 8.53 ms
8.8.8.8   16.25 (avg)   0 (drop) |||| 4.43 ms
8.8.8.8   14.88 (avg)   0 (drop) ||| 3.89 ms
8.8.8.8   13.94 (avg)   0 (drop) ||||| 5.53 ms
```

`line` mode - redraws the stats in the same line
```
♪  ./pingplot 8.8.8.8 line
8.8.8.8    9.80 (avg)   0 (drop) ||||||||||||||||||||||||| 25.7 ms
```

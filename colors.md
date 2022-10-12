# Colors

Variacijos:

-   zodis (rezervuotas terminas);
-   rgb/rgba
-   hex/hexa
-   hsl/hsla

-   hsv/hsva (paint.net, CSS nenaudojamas)

red
rgb(255, 0, 0)
#ff0000 -> #ff0000ff -> #f00f -> #f00
hsl(0, 100%, 100%)

blue
rgb(0, 0, 255)
#0000ff -> #0000ffff -> #00ff -> #00f

rgb(0, 0, 0)

# 00 00 00

rgb(1, 2, 3)

# 01 02 03

rgb(16, 0, 1)

# 10 00 01

rgb(255, 255, 255)

# ff ff ff

## Dvejetaine sistema (01)

10 -> 2
0 0000
1 0001
2 0010
3 0011
4 0100
5 0101
6 0110
7 0111
8 1000

## Sesioliktaine sistema (0123456789abcdef)

10 -> 16
0 00
1 01
2 02
...
9 09
10 0a
11 0b
12 0c
13 0d
14 0e
15 0f
16 10
17 11
18 12
19 13
20 14
21 15
22 16
23 17
24 18
25 19
26 1a
27 1b
28 1c
29 1d
30 1e
31 1f
32 20

.. 2e
.. 2f
.. 30

.. 9e
.. 9f
.. a0
.. a1

.. ee
.. ef
.. f0
.. f1

254 fe
255 ff
256 100

Yra 10 zmoniu tipai, kurie moka skaityti N-taine sistema, ir kurie nemoka

## Sesioliktaines spalvos trumpinimas

Taisykle: Kai visos dedamosios simboliu poros kartu yra savyje pasikartojancios/dubliuojasi

rgb/hex
#ff9900 -> #f90
#010203 -> #010203
#223366 -> #236
#223466 -> #223466

rgba/hexa

rgb(125, 87, 93) = rgba(125, 87, 93, [0..1])
0.34 -> #ERROR
#ff9900ff -> #f90
#010203ff -> #010203
#223366ff -> #236
#223466ff -> #223466

#ff9900cc -> #f90c
#010203ff -> #010203ff
#223366fe -> #223366fe
#223466ff -> #223466ff

#def -> #deff -> #ddeeff -> ddeeffff
#000 -> #000f -> #000000 -> #000000ff

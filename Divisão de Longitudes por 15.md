Estado inicial: 0<br>
Posição do cabeçote: < + 1 <br>
[testar módulo aqui](https://github.com/SauloSamps/TimeCalculator/blob/main/caso%201/1.txt)
| State      | `<`             | `0`           | `1`           | `⊔`           | `B`           | `C`           | `D`           | `E`             | `F`           | `G`           | `X`           |
|------------|------------------|---------------|---------------|---------------|---------------|---------------|---------------|------------------|---------------|---------------|---------------|
| 0          |                  | 0,0,R         | 0,1,R         | 1,⊔,R         | 0,B,R         | 0,C,R         | 0,D,R         | div1,E,R         | 0,F,R         | 0,G,R         | 0,X,R         |
| div1       |                  |               | div2,1,R      |               |               |               |               |                  | div16,F,L     |               |               |
| div2       |                  |               | div3,1,R      |               |               |               |               |                  |               |               |               |
| div3       |                  |               | div4,1,R      |               |               |               |               |                  |               |               |               |
| div4       |                  |               | div5,1,R      |               |               |               |               |                  |               |               |               |
| div5       |                  |               | div6,1,R      |               |               |               |               |                  |               |               |               |
| div6       |                  |               | div7,1,R      |               |               |               |               |                  |               |               |               |
| div7       |                  |               | div8,1,R      |               |               |               |               |                  |               |               |               |
| div8       |                  |               | div9,1,R      |               |               |               |               |                  |               |               |               |
| div9       |                  |               | div10,1,R     |               |               |               |               |                  |               |               |               |
| div10      |                  |               | div11,1,R     |               |               |               |               |                  |               |               |               |
| div11      |                  |               | div12,1,R     |               |               |               |               |                  |               |               |               |
| div12      |                  |               | div13,1,R     |               |               |               |               |                  |               |               |               |
| div13      |                  |               | div14,1,R     |               |               |               |               |                  |               |               |               |
| div14      |                  |               | div15,1,R     |               |               |               |               |                  |               |               |               |
| div15      |                  |               | div1,X,R      |               |               |               |               |                  |               |               |               |
| div16      |                  | div16,0,L     | div16,1,L     | div16,⊔,L     | div16,B,L     | div16,C,L     | div16,D,L     | div1_done,E,R    | div16,F,L     | div16,G,L     | div17,1,R     |
| div17      |                  | div17,0,R     | div17,1,R     | div17,⊔,R     | div17,B,R     | div17,C,R     | div17,D,R     | div17,E,R        | div17,F,R     | div18,G,R     | div17,X,R     |
| div18      |                  |               | div18,1,R     | div16,1,L     |               |               |               |                  |               |               |               |
| div1_done  |                  |               | div1_done,1,R |               |               |               |               |                  | div2_1,F,R    |               |               |
| div2_1     |                  |               | div2_2,1,R    |               |               |               |               |                  |               | div2_16,G,L   |               |
| div2_2     |                  |               | div2_3,1,R    |               |               |               |               |                  |               |               |               |
| div2_3     |                  |               | div2_4,1,R    |               |               |               |               |                  |               |               |               |
| div2_4     |                  |               | div2_5,1,R    |               |               |               |               |                  |               |               |               |
| div2_5     |                  |               | div2_6,1,R    |               |               |               |               |                  |               |               |               |
| div2_6     |                  |               | div2_7,1,R    |               |               |               |               |                  |               |               |               |
| div2_7     |                  |               | div2_8,1,R    |               |               |               |               |                  |               |               |               |
| div2_8     |                  |               | div2_9,1,R    |               |               |               |               |                  |               |               |               |
| div2_9     |                  |               | div2_10,1,R   |               |               |               |               |                  |               |               |               |
| div2_10    |                  |               | div2_11,1,R   |               |               |               |               |                  |               |               |               |
| div2_11    |                  |               | div2_12,1,R   |               |               |               |               |                  |               |               |               |
| div2_12    |                  |               | div2_13,1,R   |               |               |               |               |                  |               |               |               |
| div2_13    |                  |               | div2_14,1,R   |               |               |               |               |                  |               |               |               |
| div2_14    |                  |               | div2_15,1,R   |               |               |               |               |                  |               |               |               |
| div2_15    |                  |               | div2_1,X,R    |               |               |               |               |                  |               |               |               |
| div2_16    |                  | div2_16,0,L   | div2_16,1,L   | div2_16,⊔,L   | div2_16,B,L   | div2_16,C,L   | div2_16,D,L   | div2_17,X,R      | div2_done,F,L | div2_16,G,L   |               |
| div2_17    |                  | div2_17,0,R   | div2_17,1,R   | div2_18,⊔,R   | div2_17,B,R   | div2_17,C,R   | div2_17,D,R   | div2_17,E,R      | div2_17,F,R   | div2_17,G,R   | div2_17,X,R   |
| div2_18    |                  |               | div2_18,1,R   | div2_16,1,L   |               |               |               |                  |               |               |               |
| div2_done  | eval,<,R        | div2_done,0,L | div2_done,1,L | div2_done,⊔,L | div2_done,B,L | div2_done,C,L | div2_done,D,L | div2_done,E,L    | div2_done,F,L | div2_done,G,L | div2_done,X,L |
| eval       |                  |               |               |               |               |               |               |                  |               |               |               |

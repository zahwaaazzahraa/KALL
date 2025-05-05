# Tugas 1

Untuk membuktikan bahwa suatu pemetaan 
$T: \mathbb{R}^2 \to \mathbb{R}^2$

adalah transformasi linier, kita harus menunjukkan bahwa dua sifat berikut terpenuhi untuk semua vektor
$\vec{u}, \vec{v} \in \mathbb{R}^2$
 dan semua skalar $c \in \mathbb{R}$


#### 1. Penjumlahan Vektor:
$T(\vec{u} + \vec{v}) = T(\vec{u}) + T(\vec{v})$
#### 2. Perkalian Skalar:
$T(c \vec{v}) = cT(\vec{v})$

### Diberikan:
Pemetaan $T(v_1, v_2) = (v_1 + v_2, v_1)$
Misalkan:
$\vec{v} = (v_1, v_2) \quad \text{dan} 
\quad \vec{u} = (u_1, u_2)$


#### Langkah 1. Cek Penjumlahan Vektor:
$T(\vec{u} + \vec{v}) = T((u_1 + v_1, u_2 + v_2)) = ((u_1 + v_1) + (u_2 + v_2), u_1 + v_1) =
(u_1 + u_2 + v_1 + v_2, u_1 + v_1)$

Sementara:
$T(\vec{u}) = (u_1 + u_2, u_1), \ T(\vec{v}) = (v_1 + v_2, v_1)$

$T(\vec{u}) + T(\vec{v}) = (u_1 + u_2 + v_1 + v_2, u_1 + v_1)$

Hasilnya sama, jadi penjumlahan vektor terpenuhi.

#### Langkah 2. Cek Perkalian Skalar:
$T(c \vec{v}) = T((c v_1, c v_2)) = (c v_1 + c v_2, c v_1) = c(v_1 + v_2, v_1) = cT(\vec{v})$
Jadi, perkalian skalar juga terpenuhi.

## Kesimpulannya:
Karena kedua sifat tersebut terpenuhi, maka $T(v_1, v_2) = (v_1 + v_2, v_1)$ adalah transformasi linier.



# Tugas 2

### 1. Reflection about the x-axis

Matriks:
$\begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}$

Transformasi: $(x, y) \to (x, -y)$

Contoh:
$(2, 3) \to (2, -3)$
$(-1, 5) \to (-1, -5)$

<iframe scrolling="no" title="NO 1" src="https://www.geogebra.org/material/iframe/id/ff2cawzj/width/1280/height/537/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1280px" height="537px" style="border:0px;"> </iframe>


### 2. Reflection about the y-axis

Matriks:

$\begin{bmatrix}
-1 & 0 \\
0 & 1
\end{bmatrix}$

Transformasi: $(x, y) \to (-x, y)$

Contoh:
$(4, -2) \to (-4, -2)$

$(1, 7) \to (-1, 7)$

<iframe scrolling="no" title="NO 2" src="https://www.geogebra.org/material/iframe/id/k2npymsf/width/1280/height/537/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1280px" height="537px" style="border:0px;"> </iframe>

### 3. Reflection about the line \( y = x \)

Matriks:

$\begin{bmatrix}
0 & 1 \\
1 & 0
\end{bmatrix}$

Transformasi:  $(x, y) \to (y, x)$ 

Contoh
$(5, 2) \to (2, 5)$

$(-3, 7) \to (7, -3)$

<iframe scrolling="no" title="NO 3" src="https://www.geogebra.org/material/iframe/id/fztvnyzj/width/1280/height/537/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1280px" height="537px" style="border:0px;"> </iframe>

### 4. Reflection about the line \( y = -x \)

Matriks:
$\begin{bmatrix}
0 & -1 \\
-1 & 0
\end{bmatrix}$


Transformasi: $(x, y) \to (-y, -x)$ 

Contoh:

$(3, 4) \to (-4, -3)$

$(-5, 1) \to (-1, 5)$

<iframe scrolling="no" title="NO 4" src="https://www.geogebra.org/material/iframe/id/bkwzhfsd/width/1280/height/537/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1280px" height="537px" style="border:0px;"> </iframe>

### 5. Reflection about the origin

Matriks:
$\begin{bmatrix}
-1 & 0 \\
0 & -1
\end{bmatrix}$


Transformasi: $(x, y) \to (-x, -y)$

Contoh:

$(2, -6) \to (-2, 6)$

$(-4, 3) \to (4, -3)$

<iframe scrolling="no" title="NO 5 nw" src="https://www.geogebra.org/material/iframe/id/pttxjac4/width/1280/height/537/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1280px" height="537px" style="border:0px;"> </iframe>
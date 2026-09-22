## Гамильтониан и уравнение на собственные значения

$$
\vec B = (B_x, B_y, B_z), \qquad \vec\sigma = (\sigma_x, \sigma_y, \sigma_z)
$$

$$
\sigma_x=\begin{pmatrix}0&1\\1&0\end{pmatrix},\quad
\sigma_y=\begin{pmatrix}0&-i\\i&0\end{pmatrix},\quad
\sigma_z=\begin{pmatrix}1&0\\0&-1\end{pmatrix}
$$

$$
H = \frac{\hbar\omega}{2}\,(\vec B \cdot \vec\sigma)
$$

$$
\vec B \cdot \vec\sigma = B_x\sigma_x + B_y\sigma_y + B_z\sigma_z =
\begin{pmatrix} B_z & B_x - iB_y \\ B_x + iB_y & -B_z \end{pmatrix}
$$

$$
H = \begin{pmatrix} B_z & B_x - iB_y \\ B_x + iB_y & -B_z \end{pmatrix}
$$

$$
\det(H - EI) = 0
$$

$$
\begin{vmatrix} B_z - E & B_x - iB_y \\ B_x + iB_y & -B_z - E \end{vmatrix} = 0
$$

$$
(B_z - E)(-B_z - E) - (B_x^2 + B_y^2) = 0
$$

$$
E^2 = B_x^2 + B_y^2 + B_z^2
$$

---

## Собственные значения и собственные векторы

$$
E = \pm\sqrt{B_x^2 + B_y^2 + B_z^2}, \qquad
E_{1,2} = \pm\frac{\hbar\omega}{2}|B|, \qquad
E_1 = +|B|,\quad E_2 = -|B|
$$

$$
\begin{pmatrix} B_z & B_x - iB_y \\ B_x + iB_y & -B_z \end{pmatrix}
\begin{pmatrix} a \\ b \end{pmatrix}
= E_1 \begin{pmatrix} a \\ b \end{pmatrix}
$$

$$
B_z a + (B_x - iB_y) b = a
$$

$$
(B_x + iB_y) a - B_z b = b
$$

$$
(B_x + iB_y)\,a = b\,(1 + B_z)
\quad\Longrightarrow\quad
b = \frac{(B_x + iB_y)\,a}{1 + B_z}
$$

$$
B_z a + (B_x - iB_y)\,\frac{(B_x + iB_y)\,a}{1 + B_z} = a
$$

$$
B_z a + \frac{(B_x^2 + B_y^2)\,a}{1 + B_z} - a = 0
$$

---

## Нормировка собственных векторов (исправленный вариант)

$$
B_z + \frac{B_x^2 + B_y^2}{1 + B_z} - |B| = 0
$$

$$
\frac{B_z(|B| + B_z) + B_x^2 + B_y^2 - |B|(|B| + B_z)}{|B| + B_z} = 0
$$

$$
\frac{B_z^2 + B_x^2 + B_y^2 - |B|^2}{|B| + B_z} = 0
\quad\Longleftrightarrow\quad
B_x^2+B_y^2+B_z^2 = |B|^2
$$

$$
b = \frac{B_x + iB_y}{|B| + B_z}\,a, \qquad
a = |B| + B_z, \qquad b = B_x + iB_y
$$

$$
|E_1\rangle = \begin{pmatrix} |B| + B_z \\ B_x + iB_y \end{pmatrix}, \qquad
|E_2\rangle = \begin{pmatrix} -|B| + B_z \\ B_x + iB_y \end{pmatrix}
$$

---

## Нормировка и разложение по базису

$$
N = \sqrt{|a|^2 + |b|^2}
$$

$$
|E\rangle = \begin{pmatrix} a/N \\ b/N \end{pmatrix}, \qquad
\left|\frac{a}{N}\right|^2 + \left|\frac{b}{N}\right|^2 = \frac{|a|^2+|b|^2}{N^2} = 1
$$

$$
|\psi(0)\rangle = \sum_j \alpha_j(0)\,|E_j\rangle = \alpha_1(0)|E_1\rangle + \alpha_2(0)|E_2\rangle
$$

$$
\alpha_1(0) = \langle E_1|\psi(0)\rangle, \qquad \alpha_2(0) = \langle E_2|\psi(0)\rangle
$$

---

## Эволюция во времени

$$
|\psi(t)\rangle = \alpha_1(0)\,e^{-iE_1t/\hbar}\,|E_1\rangle + \alpha_2(0)\,e^{-iE_2t/\hbar}\,|E_2\rangle
$$

$$
|E_1\rangle = \begin{pmatrix} |B| + B_z \\ B_x + iB_y \end{pmatrix}, \qquad
|E_2\rangle = \begin{pmatrix} -|B| + B_z \\ B_x + iB_y \end{pmatrix}, \qquad
|B| = \sqrt{B_x^2 + B_y^2 + B_z^2}
$$

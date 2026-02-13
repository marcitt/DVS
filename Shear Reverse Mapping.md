Finding the reverse mapping:
$$\begin{pmatrix}
x \\ y
\end{pmatrix}
=
\begin{pmatrix}
1 & Xshear \\
Yshear & 1
\end{pmatrix}
\begin{pmatrix}
\begin{pmatrix}
x_{source}\\
y_{source}
\end{pmatrix} -
\begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
\end{pmatrix}
+
\begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
$$
Rearranging:
$$\begin{pmatrix}
x \\ y
\end{pmatrix} - \begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
=
\begin{pmatrix}
1 & Xshear \\
Yshear & 1
\end{pmatrix}
\begin{pmatrix}
\begin{pmatrix}
x_{source}\\
y_{source}
\end{pmatrix} -
\begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
\end{pmatrix}
$$
$$
\begin{pmatrix}
1 & Xshear \\
Yshear & 1
\end{pmatrix}^{-1}
\begin{pmatrix}
\begin{pmatrix}
x \\ y
\end{pmatrix} - \begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
\end{pmatrix}
+
\begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
=

\begin{pmatrix}
x_{source}\\
y_{source}
\end{pmatrix} 
$$
Final form:
$$
\begin{pmatrix}
x_{source}\\
y_{source}
\end{pmatrix}  =
\begin{pmatrix}
1 & Xshear \\
Yshear & 1
\end{pmatrix}^{-1}
\begin{pmatrix}
\begin{pmatrix}
x \\ y
\end{pmatrix} - \begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
\end{pmatrix}
+
\begin{pmatrix}
x_{centre}\\
y_{centre}
\end{pmatrix}
$$

## \#13 Proof.

We will show that $\vec{u} \cdot (\vec{v}-proj_{\vec{u}}(\vec{v}))=0$. We have:
$$\begin{align*}
	\vec{u} \cdot (\vec{v}-proj_{\vec{u}}(\vec{v}))&=\vec{u} \cdot (\vec{v}-\frac{\vec{u}\cdot\vec{v}}{\vec{u}\cdot\vec{u}}\vec{u})\\
		&=\vec{u} \cdot \vec{v} - \vec{u}\cdot\frac{\vec{u}\cdot\vec{v}}{\vec{u}\cdot\vec{u}}\vec{u}\\
		&=\vec{u}\cdot\vec{v}-(\vec{u}\cdot\vec{u})(\frac{\vec{u}\cdot\vec{v}}{\vec{u}\cdot\vec{u}})\\
		&=\vec{u}\cdot\vec{v}-\vec{u}\cdot\vec{v}\\
		&=0.
\end{align*}$$
Because $\vec{u} \cdot (\vec{v}-proj_{\vec{u}}(\vec{v}))=0$, we have $\vec{u}$ is orthogonal to $\vec{v}-proj_{\vec{u}}(\vec{v})$ for all vectors $\vec{u}$ and $\vec{v}$ in $\mathbb{R}^n$ where $u \neq 0$. $\square$

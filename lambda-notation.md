# Hyperstar Lambda Notation
--------------------

The recursive function for number comparing.

## Rules

$`P_0 = \{0\} \cup \N`$
$P_{i+1} = \{\psi_v | v \isin P_i\} \cup \{h_v(a,b) | v, a, b \isin P_i\}$
$\mathbb{A} = \bigcup_{i\isin\N_0}P_i$
$n, m \isin \N$
$\alpha, \beta, \varphi, \xi \isin \mathbb{A}$
? - any relation sign

### Lambda Rules

$\lambda_0(n)=n+1$
$\lambda_{\xi+1}(n)=\lambda^n_\xi(n)$
$\lambda_\xi(n)=\lambda_{\xi[n]}(n)$

### Gamma Rules

$h_{0}(\alpha, \beta)=\alpha+\beta$
$h_{\xi+1}(\alpha, \beta)=h^{0,\beta}_\xi(\alpha, 1)$
$h_{\xi}(\alpha, \beta)=h_{\xi[\beta]}(\alpha, \beta)$
$\gamma_\xi(\alpha)=h_{\xi}(\alpha, \alpha)$

### Fundamental Sequences

$(\xi_0+\xi_1+\dots+\xi_{k-1}+\xi_{k})[\varphi]=\xi_0+\xi_1+\dots+\xi_{k-1}+\xi_{k}[\varphi]$ only if $\xi_0\gt\xi_1\gt\dots\gt\xi_{k-1}\gt\xi_{k}$
$(\alpha[\beta])[\varphi]=\alpha[\beta[\varphi]]$
$m[\varphi]=m$
$\psi_0[\varphi]=\varphi$
$\psi_{\alpha+1}[\varphi+1]=\gamma_{\psi_{\alpha+1}[\varphi]}(\psi_{\alpha})$
$\psi_{\alpha}[\varphi]=\psi_{\alpha[\varphi]}$
$h^{0,\beta}_\xi(\alpha, \delta)[\varphi]=h^{0,\beta[\varphi]}_\xi(\alpha, \delta)$
$h_{\xi}(\alpha, \beta)[\varphi]=h_{\xi[\varphi]}(\alpha, \beta)$

### Other

$\forall n , \psi_0>n$
$\alpha ? \beta \Rightarrow \psi_\alpha?\psi_\beta$

$\exist \alpha \exist \beta , h_\alpha(\xi_0, \beta) = \xi_1 \land \beta \ge 2 \Rightarrow \xi_0 < \xi_1$

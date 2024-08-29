# The Goal

The aim of this project was to learn more about the creation and implementation of machine learning in language models. Frameworks used were Pytorch as well as the TikToken library from OpenAI. I followed Andrej Karpathy's online lectures to learn more about the implementation of the transformer architecture and made my own changes to make the model perform better on Latex, since a wider context window was required for proper formatting.

I also implemented dropout and learning rate decay for better eval performance. Ended up with some somewhat readable latex code, but more importantly gained many valuable skills in pytorch and NN training.

Bigram.ipynb --- Basic bigram model (test TikToken set up conda on MPS)

Latex-3.ipynb --- trigram model with transformer architecture

The most impressive TeX equations achieved by the model:

$$
u^{n-1}u'(0) = \lim_{n\to \infty} \frac{1}{n}\int_\Omega^{-i\alpha}ke={e^{-\alpha,ex} = 0}
$$

$$
\beta u' = -\frac{g(x)}{\lambda(x)P(x)} = Q(x)
$$

$$
t^3r = \frac{1}{2\pi} \sin k(x'-L)
$$

$$
\lambda = \int dx' p(x) f(x) \delta
$$

$$
b_n=a^{n} = a_0 \delta (x,t) + b\delta\sin{x\in L^2} = 1
$$

With only minimal context, the model managed to properly close parenthesis and brackets to have compiled code.

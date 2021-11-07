# Identificando câncer de próstata com PyCaret

![image](https://user-images.githubusercontent.com/63373520/140661669-f0b17b90-0f6f-44f5-9aaf-2d0e371638ea.png)

**O que é o `PyCaret`?**

_`PyCaret` é uma biblioteca de aprendizado de máquina de código aberto e baixo código (**low-code**) em Python que permite ir desde a preparação de seus dados até a implantação de seu modelo em minutos, na escolha do ambiente de notebook._

Essa definição se encontra no próprio site da biblioteca - é uma tradução bem literal, vou tentar deixar mais claro a definição!

O principal propósito da biblioteca é otimizar as necessidades do profissional e trazer mais "produtividade" e entrega de análises/projetos de ciência de dados, aprendizado de máquinas e etc.

A biblioteca _"encapsula"_ ou melhor possui um `pipeline` de vários modelos e roda-os simultaneamente e por fim, **ranqueia** os modelos conforme um parâmetro definido de avaliação ou não pelo usuário.

Portanto usaremos toda essa versatilidade do **PyCaret** para realizar classificação de _câncer de próstata_.

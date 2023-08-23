********************
Engenharia de prompt
********************


01.Engenharia de prompt
=======================

Engenharia de prompt é a forma com que escrevemos o nosso prompt para que seja gerada uma imagem que esperamos (e não qualquer coisa).

No Midjurney, temos o **prompt** e os **parâmetros**.

- Prompt: pequeno comando detalhando a imagem esperada.
- Parâmetros: são opções adicionada aos prompts que **mudam como a imagem é gerada**.
  - Parametros são sempre adicionados no final de um prompt. Você pode adicionar vário parâmetros em um prompt.

Imagine que você fez este pedido para um garçom "Por favor, você pode me trazer um suco de laranja sem açucar e com gelo?"

O suco de laranjá é o **que** você pede (é o prompt). Sem açucar e com gelo é o **como** (parâmetros).

- Exemplo:

.. image:: engenharia_de_prompt_prompt_V02.jpg
   :align: center
   :width: 450

Significado dos parâmetros:
 - ``--ar 2:3``: aspect ratio (proporção da imagem) - neste caso, a largura tem 2 unidades de tamanho e a altura 3. Por isso ``2:3``.

 - ``--no``: é um prompt negativo, ou seja, é o que eu **não** quero que apareça na imagem. No caso uma casa.

.. image:: engenharia_prompt_imagem_gerada.jpg
   :align: center
   :width: 450





01.a.Descrição sobre Pandas
------

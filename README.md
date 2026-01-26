![Logos MCTI, CNPEM e ILUM](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/93c3eb13-410c-40c0-a412-7096187678a4)

<h1 align='center'> Introdução à Segmentação e Reconstrução 3D de Dados de Tomografia: Abordagens Clássicas e Baseadas em Deep Learning </h1>

<h2 align="center">Iniciação à Pesquisa III</h2>


🔬 µCT • 🤖 Deep Learning • 🔄 Reconstrução Tomográfica • 🧩 Segmentação de Imagens • 📐 Análise Estrutural • 🐍 Python


**Autores:** Joana de Medeiros Oliveira Hulse Molinete e Yasmin Barbosa Shimizu.

**Contribuições:** Toda a discussão acerca do problema, entendimento e desenvolvimento do código foi realizada em conjunto pelas autoras de forma concomitante.

**Orientação:** Bruno Focassio e Yasmin Watanabe de Moura.

---

![Status](https://img.shields.io/badge/STATUS-EM%20TESTES-yellow)

## 🧬 Microtomografia Computadorizada de Raios X
A Microtomografia Computadorizada de Raios X (µCT) é uma técnica de imageamento amplamente utilizada na ciência de materiais para visualizar e quantificar a microestrutura interna de uma amostra em três dimensões. A partir de uma série de projeções bidimensionais obtidas enquanto a amostra é rotacionada (ao longo de 180° ou 360°), são gerados sinogramas que armazenam as intensidades de atenuação dos raios X. Esses sinogramas são então convertidos em um volume reconstruído por meio de algoritmos baseados na transformada de Radon inversa, como a retroprojeção filtrada (*Filtered Backprojection*, FBP), fornecendo um mapa 3D do coeficiente de atenuação em cada voxel. 
Métodos clássicos de segmentação incluem técnicas de limiarização (*thresholding*), que determinam um valor de corte no histograma de intensidades (para imagens 8-bit, de 0 a 255, variando em escala de cinza do preto ao branco) e produzem máscaras binárias que distinguem objetos de interesse do fundo. Entretanto, tanto a reconstrução quanto a segmentação podem ser afetadas por ruídos, baixa razão sinal-ruído ou artefatos característicos da tomografia, tornando necessária a aplicação de técnicas mais complexas. Nesse contexto, métodos baseados em *Deep Learning* (DL) têm emergido como alternativas poderosas para melhorar tanto a segmentação quanto o processamento e análise de dados de µCT.


## ✅ Pré-requisitos
**Ambiente:** Python 3.8+ (ideal: entre 3.8 e 3.11)

Como pré-requisitos para a utilização dos notebooks presentes nesse repositório, é necessário utilizar editor de linguagem compatível com Python 3.13, bem como instalar as versões especificadas das seguintes bibliotecas:
```bash
torch==2.0.1
deap==1.3.3
numpy==1.24.4
scikit-learn==1.3.0
tomopy==1.15.2
``` 


## 📚 Bases de dados:
`Datasets de treino, teste e validação`: dados de medidas de microtomografia de Raios X, realizados na linha de luz MOGNO do LNLS/CNPEM, disponibilizados pelo grupo de Nanobiotecnologia, sob orientação da pesquisadora Juliana S. Bernardes.


## ⚠️ Aviso:
Este repositório foi desenvolvido como um trabalho de graduação do quarto semestre do curso de Bacharelado em Ciência e Tecnologia, na matéria de Iniciação à Pesquisa, dentro do grupo de pesquisa em Simulações e Inteligência Artificial do Laboratório Nacional de Nanotecnologia (LNNano/CNPEM). 

--- 

## 🫂 Colaboradoras:
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/jojomolinetes">
        <img src="https://avatars.githubusercontent.com/u/172425100?v=4" width="120"/><br>
        <strong>Joana de Medeiros Oliveira Hulse Molinete</strong><br>
        <strong>Ilum Escola de Ciência</strong><br>
        <strong>Centro Nacional de Pesquisa em Energia e Materiais</strong><br>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/yasminbshimizu">
        <img src="https://avatars.githubusercontent.com/u/171518829?v=4" width="120"/><br>
        <strong>Yasmin Barbosa Shimizu</strong><br>
        <strong>Ilum Escola de Ciência</strong><br>
        <strong>Centro Nacional de Pesquisa em Energia e Materiais</strong><br>
      </a>
    </td>
  </tr>
</table>

# Estudo-de-curvas-de-luz-utilizando-LightKurve
🔹 O que são curvas de luz?

Uma curva de luz é um gráfico que mostra a variação do brilho de um objeto astronômico ao longo do tempo.
Essas curvas permitem detectar fenômenos como:

* Trânsitos de exoplanetas,

* Rotação estelar,

* Pulsação de estrelas variáveis,

* Atividade estelar (manchas, flares).

# Objetivo:

  Este material tem como objetivo servir de guia para a utilização da biblioteca Lightkurve no estudo de curvas de luz. Ao longo do conteúdo, será mostrado como empregar as ferramentas oferecidas pela biblioteca para a análise e manipulação de dados observacionais, com ênfase na produção de periodogramas. O objetivo é identificar periodicidades e comparar diferentes pipelines, avaliando qual fornece os resultados mais confiáveis para estudo científico.


# Alguns conceitos importantes:

🔹 Pipelines de redução de dados

Os pipelines são diferentes métodos de processamento das observações brutas feitas pelos telescópios.

Alguns exemplos utilizados neste projeto:

K2SFF: corrige o drift do telescópio com self flat fielding.

EVEREST: usa regressão baseada em pixels para remover ruído sistemático.

SPOC: pipeline oficial da NASA para TESS/K2.

K2 (bruto): dados com menos processamento, podendo conter mais ruído instrumental.

Comparar os pipelines ajuda a escolher os dados mais limpos e adequados para análise.

🔹 Missões Kepler/K2 e TESS

Kepler (2009–2018): buscou exoplanetas através da detecção de trânsitos.

K2 (2014–2018): continuação da missão Kepler, observando diferentes regiões do céu em campanhas chamadas sectors ou campaigns.

TESS (2018–presente): cobre quase todo o céu em setores de observação de 27 dias, focando em estrelas mais próximas e brilhantes.

Essas missões fornecem enormes catálogos de curvas de luz para estudos astrofísicos.

🔹 Periodicidade

A análise de curvas de luz busca detectar padrões repetitivos.

Isso é feito com periodogramas, que mostram a potência de diferentes frequências ou períodos.

O período dominante corresponde ao sinal mais forte — podendo indicar a rotação de uma estrela, a órbita de um exoplaneta ou pulsações estelares.

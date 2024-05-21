# REATOR BATELADA - CINÉTICA E CÁLCULO DE REATORES 🧪

🔹CÓDIGO #3 - Reação Enzimática com Cinética de Michaelis-Menten

📌 INTRODUÇÃO 📌

Este código realiza a simulação de uma reação de enzimática utilizando a cinética de Michaelis-Menten, um modelo comum em bioquímica para descrever a velocidade de reações catalisadas por enzimas. 

#️⃣ O MÉTODO NUMÉRICO #️⃣

Baseado na equação de Michaelis-Menten, a qual descreve a cinética de reações enzimáticas,  é uma fórmula matemática que modela a relação entre a velocidade da reação enzimática e a concentração de substrato. Pode ser expressa por:

* v = Vmax * [S] / Km + [S]

Onde:

* v é velocidade da reação (taxa de formação do produto)
* Vmax é a velocidade máxima da reação quando a enzima está saturada pelo substrato
* [S] é a concentração de substrato
* Km é a costante de Michaelis-Menten, que representa a concentração de substrato na qual a velocidade da reação é metade de Vmax

O método numérico utilizado no código é baseado na avaliação discreta da equação de Michaelis-Menten em uma faixa de valores de substrato. Essa abordagem permite simular e visualizar como a velocidade da reação varia com a concentração de substrato, ilustrando a dinâmica da cinética enzimática.

▶️ FUNCIONALIDADE DO CÓDIGO ▶️

 1. Função de cálculo da velocidade da reação:

	> def velocidade_reacao(v_max, K_m, S): calcula a velocidade da reação enzimática (v) para uma dada concentração de substrato (S) usando a cinética de Michaelis-Menten.

 2. Interação com o usuário:

	> O usuário fornece as condições iniciais DE velocidade máxima da reação e a constante de Michaelis-Menten.

 3. Faixa de concentração do substrato

	> S_min é a concentração mínima de substrato, definida como 0.

	> S_max é a concentração máxima de substrato, definida como 10 vezes K_m para garantir uma cobertura ampla da faixa onde a reação pode ser observada.

	> num_pontos define o número de pontos de dados a serem calculados dentro dessa faixa.

	> np.linspace(S_min, S_max, num_pontos) cria um array de valores de substrato uniformemente espaçados entre S_min e S_max.

 4. Simulação e Plotagem:

* O gráfico resultante ilustra a relação entre a concentração de substrato e a velocidade da reação, conforme descrito pela cinética de Michaelis-Menten.

	> Eixo x (Concentração de substrato, S): Mostra a concentração de substrato variando de S_min a S_max.

	> Eixo y (Velocidade da reação, v): Mostra a velocidade da reação correspondente a cada concentração de substrato.

	> Curva: A curva começa no ponto de origem (0,0), sobe rapidamente conforme a concentração de substrato aumenta e depois se aproxima assintoticamente de v_max, demonstrando a saturação enzimática.


💻 TECNOLOGIAS UTILIZADAS 💻 

 * Python (3.10.12)
 * Google Collab

🧑‍🔬 AUTORES 🧑‍🔬

 * DIMI FOGAÇA CANTELLI
 * GLEICI EVELLIN DE OLIVEIRA
 * PATRÍCIA LOUISE DA SILVA FERREIRA
 * TAINARA ADRIELE SCHUENKE

🔗 ACESSO AO PROJETO 🔗

https://github.com/nephhila/CCR3

# Projeto HID-43
Etapa 1 · Previsão de cargas

Carlos Alberto Monteiro da Cunha

Trabalho individual • Sistema 220/127 V • Revisão: 20/10/2026

Entrega indicada no enunciado: 27/10/2026, às 23h59. O canal deve ser confirmado no Classroom, pois o enunciado de E1 contém o campo “[CANAL DE ENTREGA]”.

## 1. Base de projeto e continuidade de E0

Este relatório desenvolve a previsão de iluminação, tomadas de uso geral (TUG) e pontos de uso específico para o vestiário, o sanitário, a cozinha e a área de serviço com DML da planta AM008.24-01.A001. Os recintos de serviço e DML são calculados separadamente e somados no resultado do conjunto.

Mantém-se o enquadramento adotado em E0: ambientes coletivos de apoio, com critérios da seção 9.5 da ABNT NBR 5410:2004 empregados POR ANALOGIA. A existência de alojamento na edificação não foi usada para estender automaticamente essa seção a todos os setores. A seção 9.1 permanece pertinente ao vestiário por conter chuveiros.

### O que foi conferido na planta

Áreas de E0 preservadas: vestiário 23,98 m²; sanitário 19,84 m²; cozinha 16,94 m²; serviço 8,56 m² e DML 1,45 m². Foram identificados seis boxes de banho, quatro lavatórios no sanitário, duas cubas na cozinha e um tanque no DML.

A cota da área de serviço é 2,75 m. Adota-se P de referência = 2 × (4,00 + 2,75) = 13,50 m, da envolvente conservadora, sem descontar recortes de DML e depósito de gás; não é uma medição do perímetro útil. A estimativa de 13,00 m de E0 também resulta em quatro TUG. Os dois símbolos circulares junto à porta PAVZ 08 pertencem ao depósito de gás, não a máquinas de lavar.

### Hipóteses e alcance

Adota-se, para esta previsão acadêmica, aquecimento elétrico nas seis duchas, uma máquina de lavar e os aparelhos de apoio discriminados nas páginas seguintes. Potências, tensões escolhidas e fatores de potência são estimativas declaradas, não dados medidos nem valores de catálogo. O fogão é considerado a gás, sem carga elétrica, com ignição manual; a planta indica depósito de gás, mas o equipamento não está especificado.

Referências conferidas no arquivo NBR-5410.pdf recebido: ABNT NBR 5410:2004, segunda edição, versão corrigida em 17/03/2008. Também foram consultados os PDFs das aulas 28, 29, 30 e 31. As páginas normativas utilizadas estão identificadas ao final; não se atribuem à norma os valores estimados dos equipamentos.

## 2. Quadro de previsão de cargas

P = potência elétrica ativa de entrada por equipamento; FP = fator de potência global adotado; I = corrente por equipamento. Iluminação e TUG são totais por recinto, lançados apenas na primeira linha. “—” nas demais linhas evita repetir cargas.

| Ambiente | Luz
pontos / VA | TUG
pontos / VA | Ponto de uso específico | P (W) | U (V) | FP | I (A) | Itens NBR¹ |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Vestiário | 1 / 340 | 4 / 1.900 | CH1 · Chuveiro elétrico | 5.500 | 220 | 1,00 | 25,00 * | L; T-e; P-a; E; C; H |
| ↳ | — | — | CH2 · Chuveiro elétrico | 5.500 | 220 | 1,00 | 25,00 * | E; C; H |
| ↳ | — | — | CH3 · Chuveiro elétrico | 5.500 | 220 | 1,00 | 25,00 * | E; C; H |
| ↳ | — | — | CH4 · Chuveiro elétrico | 5.500 | 220 | 1,00 | 25,00 * | E; C; H |
| ↳ | — | — | CH5 · Chuveiro elétrico | 5.500 | 220 | 1,00 | 25,00 * | E; C; H |
| ↳ | — | — | CH6 · Chuveiro elétrico | 5.500 | 220 | 1,00 | 25,00 * | E; C; H |
| ↳ | — | — | VE1 · Ventilador/exaustor | 100 | 127 | 0,80 | 0,98 | E |
| Sanitário | 1 / 280 | 4 / 1.900 | EX1 · Exaustor | 60 | 127 | 0,80 | 0,59 | L; T-a; P-a; E |
| ↳ | — | — | SM1 · Secador de mãos | 1.500 | 220 | 0,95 | 7,18 | E |
| Cozinha | 1 / 220 | 5 / 2.000 | RF1 · Refrigerador | 250 | 127 | 0,80 | 2,46 | L; T-b; P-a; E |
| ↳ | — | — | MO1 · Forno micro-ondas | 1.500 | 220 | 0,95 | 7,18 | E |
| ↳ | — | — | EX2 · Exaustor da cozinha | 150 | 220 | 0,80 | 0,85 | E |
| ↳ | — | — | VE2 · Ventilador de teto | 100 | 127 | 0,80 | 0,98 | E |
| Área de serviço | 1 / 100 | 4 / 1.900 | ML1 · Máquina de lavar | 1.200 | 127 | 0,80 | 11,81 * | L; T-b; P-a; E; C |
| DML | 1 / 100 | 2 / 1.200 | Sem equipamento específico | — | — | — | — | L; T-b; P-a |

¹ L = 9.5.2.1.1 e 9.5.2.1.2; T-a/b/e = alíneas de 9.5.2.2.1; P-a = 9.5.2.2.2(a); E = 4.2.1.2.1 e 4.2.1.2.3; C = 9.5.3.1; H = 9.5.2.3. Seção 9.5 utilizada por analogia. * Corrente calculada superior a 10 A.

Totais: 5 pontos de luz / 1.040 VA; 19 pontos de TUG / 8.900 VA; 14 pontos específicos / 37.860 W. Área de serviço + DML: 2 pontos de luz / 200 VA e 6 TUG / 3.100 VA.

As tomadas dedicadas aos equipamentos não integram as 19 TUG. “Ponto específico” não significa automaticamente circuito exclusivo; esse critério será aplicado na Etapa 2.

## 3. Memória de iluminação e TUG

### 3.1 Iluminação — 9.5.2.1.1 e 9.5.2.1.2

Por analogia, adota-se no mínimo um ponto fixo de luz no teto, comandado por interruptor, em cada recinto. Para A ≤ 6 m²: 100 VA. Para A > 6 m²: 100 VA + 60 VA por bloco INTEIRO adicional de 4 m². Fórmula: S = 100 + 60 × piso[(A − 6)/4]. Frações do bloco adicional não são arredondadas para cima.

| Recinto | A (m²) | Cálculo | Carga |
| --- | --- | --- | --- |
| Vestiário | 23,98 | piso[(23,98 − 6)/4] = 4; 100 + 60 × 4 | 340 VA |
| Sanitário | 19,84 | piso[(19,84 − 6)/4] = 3; 100 + 60 × 3 | 280 VA |
| Cozinha | 16,94 | piso[(16,94 − 6)/4] = 2; 100 + 60 × 2 | 220 VA |
| Área de serviço | 8,56 | piso[(8,56 − 6)/4] = 0; 100 + 60 × 0 | 100 VA |
| DML | 1,45 | 100 VA (A ≤ 6) | 100 VA |

Total: 340 + 280 + 220 + 100 + 100 = 1.040 VA. São cinco pontos mínimos de luz. Esse valor é previsão de carga, não potência real de lâmpadas nem demonstração de iluminância; quantidade final, posição e luminárias exigem estudo próprio (4.2.1.2.2).

### 3.2 Quantidade de TUG — 9.5.2.2.1

| Recinto | Alínea adotada | Cálculo / decisão | Pontos |
| --- | --- | --- | --- |
| Vestiário | e, por analogia | teto(20,00/5) = 4 | 4 |
| Sanitário | a + critério de uso | 1 ponto para cada um dos 4 lavatórios | 4 |
| Cozinha | b, por analogia | teto(16,50/3,50) = 5 | 5 |
| Área de serviço | b, por analogia | teto(13,50/3,50) = 4 | 4 |
| DML | b, local análogo | teto(4,80/3,50) = 2 | 2 |

Vestiário: sem lavatório, usa-se o critério de demais dependências com área superior a 6 m² para a quantidade; isso não afasta a seção 9.1. Sanitário: quatro pontos são escolha para uso coletivo, acima do mínimo de um ponto junto ao lavatório; a alínea (a) não exige uma tomada por cuba. Cozinha: ao menos dois dos cinco pontos sobre a bancada da pia.

### 3.3 Carga das TUG — 9.5.2.2.2(a)

Adotam-se 600 VA por ponto até os três primeiros e 100 VA nos excedentes, em cada recinto separadamente. No vestiário, adota-se o critério de carga de banheiro por conter banho, de forma conservadora. No DML, o tanque fundamenta a analogia a área de serviço. Não se utiliza a redução facultativa para dois pontos de 600 VA.

| Recinto | Memória (VA) | Total (VA) |
| --- | --- | --- |
| Vestiário | 3 × 600 + 1 × 100 | 1.900 |
| Sanitário | 3 × 600 + 1 × 100 | 1.900 |
| Cozinha | 3 × 600 + 2 × 100 | 2.000 |
| Área de serviço | 3 × 600 + 1 × 100 | 1.900 |
| DML | 2 × 600 + 0 × 100 | 1.200 |

Total de TUG: 1.900 + 1.900 + 2.000 + 1.900 + 1.200 = 8.900 VA.

## 4. Equipamentos e origem das hipóteses

Os aparelhos abaixo compõem um cenário de previsão, não uma especificação de compra. A norma não fornece estas potências ou fatores de potência. A referência geral é a previsão dos equipamentos e condições de utilização (4.2.1.2.1 e 4.2.1.2.3); cada valor adotado tem a origem indicada.

| Ponto / equipamento | Valores por unidade | Origem e decisão de projeto |
| --- | --- | --- |
| CH1–CH6<br>Chuveiro elétrico | 5.500 W<br>220 V<br>FP 1,00 | Seis duchas da planta consideradas elétricas nesta previsão. 5.500 W é estimativa por unidade; 220 V é escolha de projeto; FP 1,00 é modelo resistivo. |
| VE1<br>Ventilador/exaustor | 100 W<br>127 V<br>FP 0,80 | Uma unidade de ventilação, estimativa de 100 W; 127 V escolhido; FP 0,80 estimado para motor. |
| EX1<br>Exaustor | 60 W<br>127 V<br>FP 0,80 | Uma unidade, estimativa de 60 W; 127 V escolhido; FP 0,80 estimado para motor. |
| SM1<br>Secador de mãos | 1.500 W<br>220 V<br>FP 0,95 | Uma unidade com aquecimento e motor, estimativa de 1.500 W; 220 V escolhido; FP global 0,95 estimado. |
| RF1<br>Refrigerador | 250 W<br>127 V<br>FP 0,80 | Uma unidade, potência elétrica de entrada estimada em 250 W; 127 V escolhido; FP 0,80 estimado para o conjunto em funcionamento. |
| MO1<br>Forno micro-ondas | 1.500 W<br>220 V<br>FP 0,95 | Uma unidade, entrada elétrica estimada em 1.500 W, não potência de cocção; 220 V escolhido; FP global 0,95 estimado. |
| EX2<br>Exaustor da cozinha | 150 W<br>220 V<br>FP 0,80 | Uma unidade, estimativa de 150 W; 220 V escolhido; FP 0,80 estimado para motor. |
| VE2<br>Ventilador de teto | 100 W<br>127 V<br>FP 0,80 | Uma unidade indicada na planta, estimativa de 100 W; 127 V escolhido; FP 0,80 estimado para motor. |
| ML1<br>Máquina de lavar | 1.200 W<br>127 V<br>FP 0,80 | Uma unidade adotada, entrada elétrica estimada em 1.200 W; 127 V escolhido; FP global 0,80 estimado. Sem confirmação de modelo ou ligação hidráulica. |

### Critérios de escolha e não duplicação

220 V é adotado para chuveiros e alguns aparelhos de maior potência; 127 V para os demais modelos hipotéticos. Considera-se ligação monofásica entre fase e neutro em 127 V ou entre duas fases em 220 V. Não se aplica √3 às correntes desses equipamentos individuais. A distinção entre tensão de linha e de fase é apresentada na aula 31, páginas 5–9.

Geladeira, máquina, ventiladores e exaustores têm motor; FP 0,80 é uma hipótese de cálculo, não constante universal. Secador e micro-ondas usam FP global 0,95 estimado. Todas as potências são de entrada elétrica; não se usam potência mecânica útil nem potência de cocção.

Adota-se uma máquina de lavar como hipótese de uso, sem posição executiva definida. Os dois símbolos circulares junto à porta PAVZ 08 são do depósito de gás e não fundamentam qualquer contagem de máquinas. A posição da lavadora, sua ligação hidráulica e a compatibilidade com o depósito deverão ser verificadas na etapa de locação. No DML, o tanque não é carga elétrica; não se incluem secadora, forno elétrico ou aquecimento de pia sem previsão específica.

As seis duchas elétricas dominam a carga. Se o aquecimento for central ou a gás, as seis cargas de 5.500 W deverão ser retiradas ou substituídas pelos equipamentos efetivos, antes de dimensionar a instalação. Modelos, placas e manuais substituirão as estimativas na continuação do projeto.

## 5. Correntes dos pontos específicos

Para os equipamentos monofásicos considerados: P = U × I × FP; portanto I = P/(U × FP). A potência aparente por unidade é S = P/FP. O FP é o fator de potência global, inclusive quando existirem componentes eletrônicos. Arredonda-se apenas a apresentação final para duas casas.

| Ponto | I = P/(U × FP) | I (A) | I > 10 A? |
| --- | --- | --- | --- |
| CH1–CH6 (cada) | 5.500 / (220 × 1,00) | 25,00 | Sim |
| VE1 | 100 / (127 × 0,80) | 0,98 | Não |
| EX1 | 60 / (127 × 0,80) | 0,59 | Não |
| SM1 | 1.500 / (220 × 0,95) | 7,18 | Não |
| RF1 | 250 / (127 × 0,80) | 2,46 | Não |
| MO1 | 1.500 / (220 × 0,95) | 7,18 | Não |
| EX2 | 150 / (220 × 0,80) | 0,85 | Não |
| VE2 | 100 / (127 × 0,80) | 0,98 | Não |
| ML1 | 1.200 / (127 × 0,80) | 11,81 | Sim |

Acima de 10 A: CH1, CH2, CH3, CH4, CH5 e CH6 (25,00 A cada) e ML1 (11,81 A). São sete pontos a reservar para circuitos independentes na Etapa 2, por adoção de 9.5.3.1 por analogia. Essa previsão não define ainda cabos, disjuntores, DR ou balanceamento de fases.

Os demais pontos ficam abaixo de 10 A neste cenário, mas isso não autoriza agrupá-los sem analisar uso, fabricante e demais critérios de divisão. Correntes de partida, regime e fator de potência real dos motores não foram usados para dimensionamento nesta etapa.

### 5.1 Consolidação de cargas

| Grandeza | Resultado |
| --- | --- |
| Iluminação mínima prevista | 1.040 VA |
| TUG previstas | 8.900 VA |
| Soma das potências ativas dos pontos específicos | 37.860 W |
| Soma escalar de P/FP dos pontos específicos | 38.482,89 VA |
| Soma escalar das cargas aparentes previstas | 48.422,89 VA |

A soma escalar é um indicador conservador da carga instalada prevista, sem fator de demanda. Não é demanda calculada, não representa uma soma vetorial das potências e não deve ser dividida por uma tensão única para escolher alimentador. Não se somam diretamente os 37.860 W com os valores em VA de iluminação e TUG.

## 6. Ligação dos chuveiros — 9.5.2.3

Cada chuveiro é ligado diretamente ao ponto de utilização, por conexão apropriada à corrente e às instruções do fabricante, sem tomada e plugue. No cenário escolhido, são seis ligações diretas em 220 V. O aterramento, a equipotencialização, as restrições dos volumes da seção 9.1 e o DR de alta sensibilidade, IΔn ≤ 30 mA, previsto em E0 por 5.1.3.2.2(a), devem ser atendidos.

A localização das TUG e equipamentos do vestiário deverá ser verificada em relação aos volumes de proteção (9.1.2.1 e requisitos associados da seção 9.1). A contagem por perímetro não autoriza instalar tomadas nos boxes nem em posições proibidas.

## 7. Registro da IA e revisão

### Ponto vago corrigido — símbolos na área de serviço

A redação inicial ainda tratava genericamente as posições junto à área de serviço como equipamentos não confirmados, prolongando a ambiguidade de E0. Ao ampliar a A001, foi lida a identificação “DEPÓSITO DE GÁS” ao lado dos dois símbolos circulares. A referência a possíveis máquinas foi corrigida: esses símbolos não representam lavadoras. ML1 é apenas uma hipótese de uso adotada nesta etapa, não um aparelho extraído da planta.

### Pergunta de controle 1 — serviço e DML

Teste aplicado à solução da IA: “Posso somar as áreas de serviço e DML antes de calcular a iluminação e aplicar uma única sequência de 600/100 VA às seis TUG?” A comparação numérica mostra o problema: tratar 10,01 m² como um só recinto resultaria em 160 VA; calcular 8,56 m² e 1,45 m² separadamente resulta em 100 + 100 = 200 VA.

Nas TUG, uma única sequência para seis pontos daria 3 × 600 + 3 × 100 = 2.100 VA. A apuração separada resulta em 1.900 + 1.200 = 3.100 VA. A hipótese de agrupar foi rejeitada porque a planta mostra recintos distintos. A regra de atribuição por ambiente de 9.5.2.2.2(a), usada por analogia, foi conferida na página impressa 184 (página 192 do PDF).

### Pergunta de controle 2 — fator de potência

Teste aplicado à IA: “Uma máquina de 1.200 W em 127 V fica abaixo de 10 A se o FP for 0,80?” Usar apenas P/U daria 9,45 A e uma conclusão incorreta. A expressão completa produz 1.200/(127 × 0,80) = 11,81 A. O ponto ML1 foi, portanto, marcado acima de 10 A. Isso mostra por que não se trata motor como carga resistiva.

Este registro documenta testes de consistência efetivamente realizados. A IA foi usada para organizar e conferir a solução; a fonte normativa foi o PDF fornecido, e não a resposta da IA.

## 8. Rastreabilidade e limites da revisão

| Verificação | Situação |
| --- | --- |
| Áreas, seis duchas e recintos na A001 | Conferidos visualmente na planta recebida. |
| Memórias, unidades, somas e limiar de 10 A | Recalculados por script e comparados com valores de controle. |
| Compatibilidade com E0 | Mantida a analogia à seção 9.5; registrada a revisão do perímetro de serviço. |
| Potências, modelos e fatores de potência reais | Não disponíveis; substituídos por estimativas explícitas de projeto. |
| NBR 5410 e materiais das aulas | Itens conferidos no PDF recebido e conceitos confrontados com os slides. |
| Circuitos, cabos, disjuntores e posições definitivas | Fora da previsão de cargas; desenvolver nas próximas etapas. |

### Relação com as aulas

Aula 28, páginas 5–9: motores, fator de potência e distinção entre potência útil e absorvida. Aula 31, páginas 5–9 e 34: tensões de linha/fase e FP = P/S. Aula 29, páginas 4–6 e 24: condutores, comando e representação, a desenvolver nas etapas seguintes. Aula 30, página 17: circuitos exclusivos para cargas acima de 10 A, confrontado com 9.5.3.1.

## 9. Referências e conferência normativa

No arquivo recebido, a página do PDF corresponde à página impressa acrescida de oito. As referências abaixo foram lidas diretamente no documento normativo, sem misturar a edição de 2004 com a data da versão corrigida de 2008.

| Decisão / assunto | Item da NBR 5410:2004 | Pág. impressa / PDF |
| --- | --- | --- |
| Potência absorvida e pontos específicos | 4.2.1.2.1 e 4.2.1.2.3 | 13 / 21 |
| Critério geral de iluminação | 4.2.1.2.2 | 13 / 21 |
| DR de alta sensibilidade | 5.1.3.2.2(a) e (e), notas | 49–50 / 57–58 |
| Local de banho e volumes de proteção | 9.1.1 e 9.1.2.1 | 170–172 / 178–180 |
| Campo de aplicação; um ponto fixo de luz | 9.5.1 e 9.5.2.1.1 | 182–183 / 190–191 |
| Carga mínima de iluminação por área | 9.5.2.1.2(a) e (b) | 183 / 191 |
| Quantidade de TUG e alíneas adotadas | 9.5.2.2.1(a), (b) e (e) | 183 / 191 |
| 600 VA nos três primeiros; 100 VA excedentes | 9.5.2.2.2(a) | 184 / 192 |
| Ligação direta do aquecedor de água | 9.5.2.3 | 184 / 192 |
| Ponto dedicado com corrente superior a 10 A | 9.5.3.1 | 184 / 192 |

### Documentos utilizados

[1] E0_Monteiro.docx — levantamento individual recebido, fonte das áreas e dos critérios adotados.

[2] AM008.24-01.A001 — Plantas baixas de execução (pavimento térreo e sala de observação), PDF recebido, folha única.

[3] Projeto HID-43 — Etapa 0: Levantamento — enunciado recebido.

[4] Projeto HID-43 — Etapa 1: Previsão de cargas — enunciado recebido, entrega em 27/10/2026.

[5] ABNT. NBR 5410:2004 — Instalações elétricas de baixa tensão. Segunda edição, 30/09/2004; versão corrigida, 17/03/2008. Arquivo NBR-5410.pdf recebido, 217 páginas digitais, 209 páginas numeradas.

[6] PIMENTEL, Marcio A. S. HID-43 — Instalações Elétricas. PDFs das aulas 28 (25 páginas), 29 (35 páginas), 30 (22 páginas) e 31 (65 páginas), recebidos como material de apoio da disciplina. Foram consultados os slides, sem alegação de reprodução dos vídeos.

Não foram utilizados catálogos como fonte de potência. Os valores estimados são hipóteses autorais desta previsão, apresentadas para permitir revisão e substituição sem alterar o método.

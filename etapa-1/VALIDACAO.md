# Revisão da Etapa 1

Revisão em 20/10/2026, a partir dos documentos fornecidos.

## Cobertura do enunciado

| Item solicitado | Onde consta na entrega |
| --- | --- |
| Iluminação: quantidade, VA e memória pela área | Seções 2 e 3.1 |
| TUG: quantidade, perímetro/lavatórios/alínea e VA | Seções 2, 3.2 e 3.3 |
| Equipamentos: potência, tensão, FP e origem | Seções 2 e 4 |
| Correntes e identificação acima de 10 A | Seção 5 |
| Ligação do chuveiro | Seção 6 |
| Registro crítico da IA | Seção 7 |
| Referências normativas verificáveis | Seção 9 |

## Verificações realizadas

- Leitura do trabalho E0 e dos dois enunciados recebidos em Word.
- Inspeção visual ampliada da planta, inclusive do depósito de gás e da cota de 2,75 m.
- Leitura dos itens aplicáveis no PDF NBR 5410, edição de 2004, versão corrigida de 2008.
- Consulta aos quatro PDFs das aulas e inspeção visual das fórmulas relevantes que são imagens.
- Recálculo com `Decimal`, sem arredondamento intermediário.
- Valores de controle por recinto:
  - iluminação: 340, 280, 220, 100 e 100 VA;
  - TUG: 1.900, 1.900, 2.000, 1.900 e 1.200 VA.
- Contagem de 14 pontos específicos com identificadores únicos.
- Verificação de I = P/(U × FP), com 25 A por chuveiro e 11,81 A na lavadora.
- Caso de controle da lavadora: sem FP daria 9,45 A e mudaria incorretamente a classificação de 10 A.
- Teste de separação serviço/DML: 200 VA e 3.100 VA, em vez de 160 VA e 2.100 VA.
- Verificação das somas e da distinção entre W, VA e demanda.
- Geração do Word e conversão efetiva em PDF com LibreOffice.
- Revisão visual das páginas e conferência de texto, quadro, referências e unidades no PDF.

## Hipóteses que permanecem no projeto

As estimativas são permitidas pelo item 3 do enunciado, desde que declaradas.
Não constituem falha de cálculo, mas precisam de confirmação na continuação:

1. Seis duchas elétricas de 5.500 W em 220 V, FP 1.
2. Uma lavadora de 1.200 W em 127 V, FP 0,80, ainda sem posição executiva.
3. Aparelhos de apoio com potências e FP estimados, conforme a tabela de premissas.
4. Fogão a gás, ignição manual, sem carga elétrica; coerente com o depósito de gás, sem modelo definido.
5. Perímetro conservador de referência de 13,50 m na área de serviço.
   Não é apresentado como medição do contorno útil; o valor aproximado de E0 também gera quatro TUG.
6. A carga de 1.040 VA é previsão mínima de iluminação por analogia, não projeto luminotécnico.

O trabalho não contém dimensionamento executivo de circuitos, cabos, proteções,
aterramento, alimentadores ou demanda, pois essas decisões não pertencem à Etapa 1.

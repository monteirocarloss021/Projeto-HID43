# Projeto HID-43 — instalações elétricas

**Carlos Alberto Monteiro da Cunha** · trabalho individual · alimentação 220/127 V.

Projeto acadêmico dos ambientes de apoio da planta AM008.24-01.A001:
vestiário, sanitário, cozinha e área de serviço com DML.

## Entrega da Etapa 1

- [Word editável — E1_Monteiro.docx](entregas/E1_Monteiro.docx)
- [PDF para entrega — E1_Monteiro.pdf](entregas/E1_Monteiro.pdf)
- [Relatório navegável e memória de cálculo](etapa-1/relatorio.md)
- [Quadro de cargas em CSV](etapa-1/quadro_cargas.csv)

Prazo indicado no enunciado: **27/10/2026, às 23h59**.
O enunciado pede PDF. Foi preservada a autoria individual de E0 no nome `E1_Monteiro`.
O canal de E1 aparece como `[CANAL DE ENTREGA]`; verificar a postagem da atividade.

## Resultado do cenário adotado

| Grandeza | Resultado |
| --- | ---: |
| Pontos mínimos de iluminação | 5 |
| Carga mínima de iluminação | 1.040 VA |
| Pontos de TUG | 19 |
| Carga prevista das TUG | 8.900 VA |
| Pontos de uso específico | 14 |
| Potência ativa dos equipamentos específicos | 37.860 W |
| Soma escalar das cargas aparentes previstas | 48.422,89 VA |
| Pontos com corrente calculada acima de 10 A | 6 chuveiros + 1 lavadora |

Os valores são uma **previsão de cargas com hipóteses explícitas**, não um dimensionamento
de alimentadores, condutores ou proteções. A soma escalar em VA não é demanda calculada.

## Decisões e revisão

- Mantido o critério de E0: seção 9.5 da NBR 5410 aplicada **por analogia** aos ambientes coletivos.
- Itens conferidos no `NBR-5410.pdf` recebido: edição de 2004, versão corrigida de 17/03/2008.
  O relatório identifica tanto a página impressa quanto a página do PDF.
- Área de serviço e DML calculados separadamente: 200 VA de iluminação e 3.100 VA de TUG no conjunto.
- O vestiário usa o critério de quantidade de 9.5.2.2.1(e), por não ter lavatório;
  adota-se conservadoramente a potência de TUG de local de banho, 9.5.2.2.2(a).
- No sanitário, quatro TUG correspondem à decisão de atender os quatro lavatórios;
  não se atribui à norma uma exigência de uma tomada por cuba.
- Corrigida a leitura de E0: os dois símbolos circulares junto à porta PAVZ 08 são
  do depósito de gás, não são máquinas de lavar.
- Potências, FP, tensões dos aparelhos e seis duchas elétricas são **estimativas e escolhas de projeto**,
  sem inventar modelos ou catálogos. Há apenas uma lavadora hipotética.
- Os chuveiros têm ligação direta, sem tomada e plugue.
- Foram lidos os PDFs das aulas 28, 29, 30 e 31. Não se declara ter assistido aos vídeos.

## Organização

| Caminho | Conteúdo |
| --- | --- |
| `documentos/originais/` | Anexos recebidos, preservados |
| `documentos/fontes.sha256` | Integridade dos originais |
| `etapa-0/revisao.md` | Síntese e conferência de E0, sem alterar o original |
| `etapa-1/dados.json` | Áreas, perímetros de referência, quantidades e equipamentos |
| `etapa-1/relatorio.md` | Versão textual integral da entrega |
| `etapa-1/quadro_cargas.csv` | Quadro com uma linha por equipamento |
| `etapa-1/resultados.json` | Resultados sem arredondamento intermediário |
| `etapa-1/VALIDACAO.md` | Critérios e evidências da revisão |
| `scripts/gerar_etapa1.py` | Cálculo, verificações e geração do Word |
| `entregas/` | Word e PDF finais |

## Reproduzir a entrega

Requisitos: Python 3.10 ou superior, `python-docx==1.2.0` e LibreOffice para o PDF.

Na raiz deste repositório:

```bash
python -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
.venv/bin/python scripts/gerar_etapa1.py
soffice --headless --convert-to pdf --outdir entregas entregas/E1_Monteiro.docx
```

O script verifica as fórmulas, totais, contagem dos equipamentos, separação de recintos
e pontos acima de 10 A antes de escrever a entrega. Para modificar premissas, editar
`etapa-1/dados.json` e rever os valores de controle e os textos dependentes no script.
Os controles registram o cenário desta entrega e devem falhar se ele mudar sem revisão.
O documento gerado não deve ser editado manualmente quando se pretende regenerá-lo.

## Continuidade

Na Etapa 2: confirmar modelos e aquecimento das duchas; definir a posição da lavadora;
locar pontos observando os volumes do vestiário e o depósito de gás; dividir circuitos,
verificar DR e distribuir as cargas pelas fases.
As hipóteses de potência devem ser substituídas por placas ou catálogos antes do
dimensionamento definitivo.

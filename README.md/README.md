# Orçamento Imobiliário - UniFECAF

Projeto em Python para geração de orçamento de aluguel mensal, com aplicação de Programação Orientada a Objetos, validação de entradas e exportação de arquivo CSV com as 12 parcelas do orçamento.

## Estrutura
- `src/main.py`: aplicação principal
- `docs/`: relatório, fluxograma e materiais de apoio
- `data/`: pasta reservada para arquivos de teste

## Conceitos aplicados
- `if / elif / else`
- laços de repetição e validação de entrada
- classes abstratas (`ABC`)
- `@dataclass`
- composição entre objetos
- geração de arquivo `.csv`

## Como executar
```bash
cd src
python main.py
```

## O que o programa faz
1. Solicita o tipo de imóvel.
2. Recebe os dados necessários para o cálculo.
3. Calcula aluguel e parcela do contrato.
4. Gera 12 linhas de parcelas em CSV.
5. Salva o arquivo na Área de Trabalho.

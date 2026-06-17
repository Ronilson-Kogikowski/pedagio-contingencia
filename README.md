# Simulador de Contingência — Nova Rota do Oeste

Simulador interativo para treinamento de operadores de pedágio em cenários de contingência por falta de energia elétrica.

## Sobre

Este projeto simula uma praça de pedágio em situação de emergência (falta de energia), permitindo que operadores pratiquem os procedimentos de arrecadação manual, liquidação de turno e prestação de contas sem a necessidade de um ambiente real.

O simulador reproduz o fluxo de veículos em 4 faixas (AVI, Mista, L3 e L4), com controle manual de cancelas, ajuste de volume de tráfego e ativação do plano de contingência.

## Funcionalidades

- **Simulação visual** de tráfego em tempo real com diferentes tipos de veículos (carros, caminhões, ônibus, motos)
- **Controle de cancelas** individual por faixa
- **Cenários prontos**: Operação Normal e Plano de Contingência
- **Ajuste de volume de tráfego**: Leve, Médio e Severo
- **Guia do Operador** com checklist passo a passo do protocolo de contingência
- **Liquidação Final** com procedimentos de encerramento de turno
- **Prestação de Contas** para retorno da energia elétrica
- **Design responsivo** com suporte para dispositivos móveis
- **Atalhos de teclado**: `C` contingência, `R` normal, `1-4` faixas

## Páginas

| Página | Descrição |
|---|---|
| `index.html` | Simulador visual com canvas interativo |
| `operador.html` | Guia do operador com checklist de 9 etapas |
| `liquidacao.html` | Procedimentos de liquidação final do turno |
| `prestacao_contas.html` | Prestação de contas após retorno da energia |

## Como usar

Abra o `index.html` em qualquer navegador moderno. O simulador funciona inteiramente no lado do cliente, sem necessidade de servidor.

## Tecnologias

HTML5, CSS3, JavaScript (Canvas API)

---

Desenvolvido por Ronilson K. Brizola

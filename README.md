  # Projeto de Detecção

Neste projeto, abordamos a questão de um site que apresentava ineficiências na conexão com seus clientes, resultando em lentidão durante o uso.

## Objetivo

O principal objetivo deste projeto é identificar e quantificar o tempo de resposta do processo de login, medindo em milissegundos. Através dessa análise, conseguimos localizar os pontos críticos que estavam causando a demora e, assim, propor melhorias para otimizar a experiência do usuário.

## Descrição do Problema

A lentidão no processo de login pode impactar negativamente a satisfação do cliente e, consequentemente, a retenção de usuários. Com isso em mente, desenvolvemos um código que monitora o tempo necessário para completar o login, permitindo uma análise detalhada do desempenho do sistema.

## Metodologia

- **Coleta de Dados**: Utilizamos um conjunto de dados fictícios que simula o comportamento dos usuários no site.
- **Análise Estatística**: Aplicamos técnicas de agrupamento e agregação para calcular métricas como tempo mínimo, máximo, médio, mediano, e desvios padrão do tempo de acesso.
- **Visualização**: Criamos gráficos para ilustrar o status dos usuários e as avaliações do sistema, facilitando a interpretação dos dados.

## Resultados

Os resultados obtidos através da análise nos permitiram identificar os principais gargalos no processo de login, possibilitando a implementação de soluções que visam melhorar a eficiência do sistema.

## Conclusão

Este projeto não apenas destaca a importância de monitorar o desempenho de sistemas online, mas também fornece uma base sólida para futuras melhorias e otimizações. Através da detecção de ineficiências, podemos garantir uma experiência mais fluida e satisfatória para os usuários.

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- NumPy
- SymPy

## Como Executar

Para executar o projeto, siga os passos abaixo:

Clone o repositório:
```bash
git clone https://github.com/Zeryoss/Analise_Gargalos.git
```
Navegue até o diretório do projeto:
```bash
cd Analise_Gargalos
```
Instale as dependências necessárias:
```bash
pip install -r requirements.txt
```
Execute o script principal:
```bash
python Analise_Gargalos_AG0.py
```

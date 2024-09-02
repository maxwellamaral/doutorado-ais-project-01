# Relatório Técnico Projeto 01 - Análise de Imagens de Satélite

## Problema Prático 1: "Monitoramento da Degradação Florestal na Caatinga Utilizando Imagens Multiespectrais"

Maxwell Anderson Ielpo do Amaral

### 1. Introdução

**Contextualização:**

Este projeto tem como objetivo monitorar a degradação florestal na região da Caatinga utilizando imagens de satélite das missões Landsat 8 e Sentinel-2, e técnicas de sensoriamento remoto para calcular o Índice de Vegetação por Diferença Normalizada (NDVI). Além disso, o MapBiomas foi usado para analisar as mudanças no uso da terra e fragmentação florestal ao longo do tempo.

**Descrição do Problema:**

A Caatinga é o bioma semiárido mais biodiverso do mundo, ocupando cerca de 11% do território brasileiro. Este bioma, no entanto, sofre com a degradação florestal, que tem impactos significativos na biodiversidade e nos modos de vida das comunidades locais. Monitorar essa degradação ao longo do tempo é crucial para a implementação de políticas de conservação e para o entendimento das dinâmicas ambientais na região.

**Objetivo Geral:**

Desenvolver uma análise temporal da evolução do NDVI na Caatinga para identificar áreas de degradação florestal e quantificar as mudanças de fragmentação da vegetação utilizando métricas como o Número de Fragmentos (NP) e Índice de Fragmentação.

**Objetivos Específicos:**

1. Aquisição de Dados: Utilizar o Google Earth Engine para acessar e baixar imagens de satélite da missão Landsat 8 e Sentinel-2 (estudá-las!), da região da Caatinga, desde 2017.
2. Pré-processamento: Realizar o cálculo do NDVI para todas as imagens adquiridas.
3. Análise Temporal: Desenvolver uma análise temporal da evolução do NDVI na região, identificando áreas de possível degradação florestal ao longo do tempo.
4. Mapeamento de Áreas Degradadas: Utilizando imagens do MapBiomas e o  Fragstat com imagens do SLC, mapear as áreas que apresentam aumento significativo do índice de fragmentação de floresta durante o período estudado. Repita utilizando agora imagens da Scene Classification Layer (SCL) do Sentinel-2 para o cálculo do índice de fragmentação do Fragstat.
5. Relatório: Elaborar um relatório técnico que inclua todos os passos realizados, as metodologias aplicadas, os resultados obtidos e uma discussão sobre a relevância dos achados.

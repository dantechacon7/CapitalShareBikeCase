# Bike Sharing Demand Analysis

Exploratory SQL analysis of bike rental behavior in Washington D.C., investigating how weather, seasonality, temperature, and time patterns influence demand among casual riders and registered users.

[EN](#en-overview) • [PT-BR](#pt-br-visão-geral)

---

# EN Overview

## 🎯 Objective

Understand the factors that influence bike rental demand and identify behavioral differences between casual and registered users.

---

## 🛠 Tech Stack

* SQL
* Relational databases
* Window functions
* Date and time transformations

---

## 🔍 Analytical Process

The analysis included:

* Datetime decomposition (date and time components)
* Data cleaning and removal of redundant columns
* Category mapping using CASE WHEN
* Segmentation by weather conditions, weekdays, and holidays
* Temporal analysis by hour, season, and month

---

## 📊 Main Questions

* Which weather conditions maximize demand?
* How does temperature affect rentals?
* What are the differences between casual and registered riders?
* Which periods concentrate the highest demand?
* How do wind conditions influence usage?

---

## 💡 Key Insights

### ☀️ Sunny weather drives demand

Sunny days generated the highest rental volume for both casual and registered users.

---

### 🌡 Mild temperatures increase rentals

Temperatures between 20°C and 29°C showed the highest usage levels, especially during spring and autumn.

---

### 📅 Different behaviors by customer type

* Registered users concentrated rides during weekdays and commuting hours.
* Casual users rented more frequently during weekends.

---

### 🌬 Wind and cold temperatures

Unexpectedly, stronger winds combined with lower temperatures were associated with increased rentals among registered users.

---

## 📈 Variables Analyzed

* Weather conditions
* Temperature
* Seasons
* Day of week
* Holidays
* Hour of day
* Wind speed

---

## 🚨 Use Cases

* Demand forecasting
* Urban mobility analysis
* Customer segmentation
* Seasonality analysis
* Transportation behavior analytics

---

# PT-BR Visão Geral

## 🎯 Objetivo

Compreender os fatores que influenciam a demanda por bicicletas compartilhadas e identificar diferenças comportamentais entre usuários casuais e mensalistas.

---

## 🔍 Processo Analítico

A análise contemplou:

* Transformações em colunas de data e hora
* Limpeza e remoção de colunas redundantes
* Mapeamento de categorias com CASE WHEN
* Segmentação por clima, dias da semana e feriados
* Análise temporal por hora, estação e mês

---

## 💡 Principais insights

### ☀️ Clima ensolarado concentra a maior demanda

Dias ensolarados apresentaram o maior número de locações entre ambos os perfis de usuários.

### 🌡 Temperaturas amenas são as preferidas

As faixas entre 20°C e 29°C concentraram o maior volume de locações.

### 📅 Perfis diferentes de utilização

* Usuários mensalistas concentram viagens em dias úteis e horários de pico.
* Usuários casuais apresentam maior utilização nos finais de semana.

### 🌬 Ventos fortes e temperaturas baixas

Foi observada uma associação positiva entre ventos mais fortes e maior utilização por mensalistas em dias frios.

---

## 📈 Variáveis analisadas

* Clima
* Temperatura
* Estações do ano
* Dias da semana
* Feriados
* Horários
* Velocidade do vento

---

## 🚨 Casos de uso

* Forecast de demanda
* Mobilidade urbana
* Segmentação de clientes
* Análise de sazonalidade
* Behavioral Analytics

# Doppler no Morfológico do 1º trimestre: calculadora de percentis

Calculadora simples e gratuita para a pós-graduação em Medicina Fetal.
Informe a idade gestacional (semanas e dias) e, ao escolher, o IP das artérias uterinas direita e esquerda e/ou o IPV do ducto venoso. Para as uterinas, a página devolve o percentil e os valores de P5, P50 e P95 daquela idade gestacional; para o ducto venoso, indica se o IPV está acima do P95 da semana.

Funciona inteiramente no navegador: nenhum dado é enviado, salvo ou armazenado.

## Artérias uterinas (IP médio), 11 a 41 semanas

Gómez O, Figueras F, Fernández S, Bennasar M, Martínez JM, Puerto B, Gratacós E. Reference ranges for uterine artery mean pulsatility index at 11–41 weeks of gestation. *Ultrasound Obstet Gynecol* 2008;32(2):128-132. doi:10.1002/uog.5315

- ln(IP médio) esperado = 1,39 − 0,012×IG + 0,0000198×IG² (IG em dias)
- desvio-padrão do ln = 0,272 − 0,000259×IG
- percentil a partir do z-score da distribuição log-normal

## Ducto venoso (IPV), 11+0 a 14+0 semanas

- P95 por semana completa de IG: 11s = 1,46; 12s = 1,33; 13s = 1,32; 14s = 1,39
- valores de referência fornecidos no curso de pós-graduação em Medicina Fetal
- a calculadora só informa se o IPV está acima do P95 da semana; não calcula percentil do ducto venoso

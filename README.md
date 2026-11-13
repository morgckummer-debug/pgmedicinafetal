# Doppler no Morfológico do 1º trimestre: calculadora de percentis

Calculadora simples e gratuita para a pós-graduação em Medicina Fetal.
Informe a idade gestacional (semanas e dias) e, ao escolher, o IP das artérias uterinas direita e esquerda e/ou o IPV do ducto venoso. Para as uterinas, a página devolve o percentil e os valores de P5, P50 e P95 daquela idade gestacional; para o ducto venoso, o percentil a partir dos valores de Carvalho et al. (2004).

Funciona inteiramente no navegador: nenhum dado é enviado, salvo ou armazenado.

## Artérias uterinas (IP médio), 11 a 41 semanas

Gómez O, Figueras F, Fernández S, Bennasar M, Martínez JM, Puerto B, Gratacós E. Reference ranges for uterine artery mean pulsatility index at 11–41 weeks of gestation. *Ultrasound Obstet Gynecol* 2008;32(2):128-132. doi:10.1002/uog.5315

- ln(IP médio) esperado = 1,39 − 0,012×IG + 0,0000198×IG² (IG em dias)
- desvio-padrão do ln = 0,272 − 0,000259×IG
- percentil a partir do z-score da distribuição log-normal

## Ducto venoso (IPV), 11+0 a 14+6 semanas

- Referência: Carvalho FHC, Moron AF. Valores dos parâmetros da dopplerfluxometria do ducto venoso entre a 10ª e a 14ª semana de gestações normais. Rev Bras Ginecol Obstet 2004;26(1):15-20 (276 gestações)
- Percentis 5, 50 e 95 do índice de pulsatilidade por semana completa de IG (Tabela 1 do artigo): 11s = 1,03 / 1,08 / 1,46; 12s = 1,06 / 1,09 / 1,33; 13s = 1,05 / 1,09 / 1,32; 14s = 1,03 / 1,06 / 1,39
- entre P5 e P95, o percentil é aproximado por uma distribuição normal dividida; fora da faixa sai "< P5" ou "> P95"

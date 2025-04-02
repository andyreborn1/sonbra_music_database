# SONBRA Database
Este repositório contém **4000 amostras** de registros da base de dados SOBRA.
Possui as caracteríticas extraídas de 100 faixas musicais únicas, de cada um dos 8 gêneros contidos na base. Cada faixa foi dividida em segmentos de 30 segundos.

## Especificações

### Estatíticas da base
| Métrica | Valor |
|--------|-------|
| Total de amostras | 4,000 |
| Faixas originais | 100 |
| Gêneros representados | 8 |
| Segmentos por faixa | 5 |
| Duração dos segmentos | 30s |

### Distribuição de gêneros
O dataset possui uma distribuição balanceada dos gêneros:
1. Bossa Nova
2. Forró
3. Funk
4. Pagode
5. Pisadinha
6. Samba
7. Samba-enredo
8. Sertanejo

### Estrutura dos seguimentos
1. Begin - 30 segundos iniciais
2. Middle_1 - 30 segundos antes do ponto central
3. Middle - 15 segundos antes e depois do ponto central
4. Middle_2 - 30 segundos antes do ponto central
5. End - 30 segundos finais

### Caracteríticas extraídas
- RMS
- ZCR
- ZCR Sum
- Mel spectrogram
- Spectral bandwidth
- Spectral centroid
- Spectral rolloff
- Chroma STFT
- Chroma CQT
- Chroma CENS
- Tonnetz
- Tempogram
- Fourier Tempogram
- MFCC

# Binary Masks (Consensus Ground Truth) / Máscaras Binárias (Consenso)

## 🇺🇸 English
This folder contains the **final binary consensus masks** used to train and test the ASRDNet model.
These masks were derived from the voting data in the `probabilistic_mask` folder using a majority vote logic.

**Consensus Logic:**
A pixel is labeled as **Lesion (Value 1 / White)** if it was marked by **two or more** experts. Otherwise, it is labeled as **Background (Value 0 / Black)**. This ensures a robust and high-quality ground truth.

## 🇧🇷 Português
Esta pasta contém as **máscaras binárias de consenso final** usadas para treinar e testar o modelo ASRDNet.
Estas máscaras foram derivadas dos dados de votação na pasta `probabilistic_mask` utilizando uma lógica de voto majoritário.

**Lógica de Consenso:**
Um pixel é rotulado como **Lesão (Valor 1 / Branco)** se foi marcado por **dois ou mais** especialistas. Caso contrário, é rotulado como **Fundo (Valor 0 / Preto)**. Isso garante um *ground truth* robusto e de alta qualidade.

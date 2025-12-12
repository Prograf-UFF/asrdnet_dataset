# ASRDNet Dataset: Asian Soybean Rust Segmentation

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 🇺🇸 English Description

This repository contains the dataset used in the paper **"ASRDNet: A new image-segmentation neural network model for detecting Asian rust on soybean leaves"**. The dataset consists of 63 high-resolution RGB images of soybean leaves infected with Asian Soybean Rust (ASR), caused by the fungus *Phakopsora pachyrhizi*.

The images were provided by **Embrapa** and annotated by three independent expert phytopathologists. The goal of this dataset is to provide a benchmark for semantic segmentation of plant diseases, specifically dealing with lesion morphology variations.

### Directory Structure

The dataset is organized into three main folders:

1.  **`original_images/`**: Contains the raw RGB images of the leaves.
2.  **`probabilistic_mask/`**: Contains masks representing the vote count of the 3 experts (agreement level).
3.  **`binary_mask/`**: Contains the final consensus (2 votes or more) binary masks used for model training (lesion vs. background).

### File Naming
All folders contain 63 images, named consistently from `image1.png` to `image63.png` to ensure easy matching between input and ground truth.

---

## 🇧🇷 Descrição em Português

Este repositório contém o conjunto de dados utilizado no artigo **"ASRDNet: A new image-segmentation neural network model for detecting Asian rust on soybean leaves"**. O conjunto de dados consiste em 63 imagens RGB de alta resolução de folhas de soja infectadas com a Ferrugem Asiática da Soja (ASR), causada pelo fungo *Phakopsora pachyrhizi*.

As imagens foram fornecidas pela **Embrapa** e anotadas por três fitopatologistas especialistas independentes. O objetivo deste conjunto de dados é fornecer um *benchmark* para a segmentação semântica de doenças de plantas, lidando especificamente com variações na morfologia das lesões.

### Estrutura de Diretórios

O conjunto de dados está organizado em três pastas principais:

1.  **`original_images/`**: Contém as imagens RGB brutas das folhas.
2.  **`probabilistic_mask/`**: Contém máscaras que representam a contagem de votos dos 3 especialistas (nível de concordância).
3.  **`binary_mask/`**: Contém as máscaras binárias de consenso final (2 votos ou mais) utilizadas para o treinamento do modelo (lesão vs. fundo).

### Nomenclatura dos Arquivos
Todas as pastas contêm 63 imagens, nomeadas consistentemente de `image1.png` a `image63.png` para garantir a fácil correspondência entre a imagem de entrada e a máscara (*ground truth*).

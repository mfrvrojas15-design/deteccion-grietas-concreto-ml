# 🏗️ Detección Automática de Grietas en Estructuras de Concreto

![Banner del proyecto](banner.png)

## 👩‍💻 Autores

María Fernanda Rojas, Angie Boada

## 🎯 Objetivo

Desarrollar un modelo de aprendizaje de máquina capaz de detectar automáticamente si una imagen de una estructura de concreto presenta grieta o no presenta grieta.

## 🗂️ Dataset

El proyecto utiliza un dataset de imágenes de superficies de concreto clasificadas en dos categorías:

- ✅ Sin grieta
- ⚠️ Con grieta

Las imágenes fueron procesadas mediante conversión a escala de grises, redimensionamiento a **28x28 píxeles**, normalización y aplanamiento en vectores de **784 características**.

### 🔗 Link de descarga del dataset

https://www.kaggle.com/datasets/arunrk7/surface-crack-detection/data

## 🤖 Modelos

- 🌳 Decision Tree
- 🌲 Random Forest
- 📐 SVM
- 🧠 Deep Learning
- 📉 PCA
- 🔵 KMeans
- 🧩 DBSCAN

## 📌 Descripción del proyecto

Este proyecto aplica técnicas de aprendizaje de máquina para clasificar imágenes de concreto según la presencia o ausencia de grietas.

Primero se trabajó con modelos supervisados como **Decision Tree**, **Random Forest**, **SVM** y **Deep Learning**. Estos modelos fueron entrenados con imágenes etiquetadas para aprender patrones asociados a grietas en el concreto.

Luego se aplicaron técnicas de aprendizaje no supervisado y reducción de dimensionalidad. Se usó **PCA** para reducir las imágenes de **784 características** a **2 componentes principales**, permitiendo visualizar el dataset en un plano bidimensional. Posteriormente, se aplicaron **KMeans** y **DBSCAN** para analizar agrupamientos naturales dentro de los datos.

## 🔗 Enlaces

- 💻 Código del proyecto: [Proyecto_APMaquina.ipynb](Proyecto_APMaquina.ipynb)
- 📊 Diapositivas: [diapositivas.pdf](diapositivas.pdf)
- 🎥 Video de sustentación: [Agregar link de YouTube]
- 📁 Repositorio: [deteccion-grietas-concreto-ml](https://github.com/mfrvrojas15-design/deteccion-grietas-concreto-ml)

## 📂 Archivos del repositorio

- 📓 `Proyecto_APMaquina.ipynb`: notebook principal del proyecto.
- 🖼️ `banner.png`: imagen principal del proyecto.
- 📑 `diapositivas.pdf`: presentación del proyecto.
- 📝 `README.md`: descripción general del proyecto.

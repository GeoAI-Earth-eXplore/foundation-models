# Foundation Models

A curated collection of foundation models for GeoAI, Earth observation, remote sensing, and geospatial applications.

The goal of this repository is to make relevant foundation models easier to discover and compare across different research and application areas.

## Categories

- [Earth Observation Foundation Models](#earth-observation-foundation-models)
- [Multimodal and Multisensor Models](#multimodal-and-multisensor-models)
- [Vision Foundation Models for GeoAI](#vision-foundation-models-for-geoai)
- [Embedding and Representation Models](#embedding-and-representation-models)
- [Benchmarks and Evaluation](#benchmarks-and-evaluation)

---

## Earth Observation Foundation Models

| Resource | Description | Organization | Modality / Input | Access |
|---|---|---|---|---|
| [Prithvi](https://huggingface.co/ibm-nasa-geospatial) | Earth observation foundation model family developed for geospatial and environmental applications. | IBM / NASA | Multispectral, multitemporal Earth observation data | Open / research |
| [TerraMind](https://github.com/ibm/terramind) | Multimodal Earth observation foundation model designed for geospatial representation learning and downstream tasks. | IBM / ESA | Multimodal Earth observation | Open / research |
| [AnySat](https://github.com/gastruc/AnySat) | Foundation model designed to learn transferable representations across multiple Earth observation sensors and resolutions. | Research project | Multisensor, multiresolution remote sensing | Open / research |
| [AgriFM](https://github.com/flyakon/AgriFM) | Foundation model focused on agricultural remote sensing and downstream geospatial applications. | Research project | Agricultural Earth observation | Open / research |
| [AlphaEarth Foundations](https://deepmind.google/discover/blog/alphaearth-foundations-helps-map-our-planet-in-unprecedented-detail/) | Earth representation model designed to generate reusable geospatial embeddings for large-scale mapping and analysis. | Google DeepMind | Multisource Earth observation | Research / platform dependent |

---

## Multimodal and Multisensor Models

| Resource | Description | Organization | Modality / Input | Access |
|---|---|---|---|---|
| [TerraMind](https://github.com/ibm/terramind) | Multimodal Earth observation foundation model supporting multiple geospatial data modalities. | IBM / ESA | Multimodal Earth observation | Open / research |
| [AnySat](https://github.com/gastruc/AnySat) | Sensor-agnostic foundation model for learning representations across different Earth observation sources. | Research project | Multisensor, multiresolution, multitemporal | Open / research |

---

## Vision Foundation Models for GeoAI

| Resource | Description | Organization | Modality / Input | Access |
|---|---|---|---|---|
| [DINOv3 Satellite ViT-7B](https://huggingface.co/facebook/dinov3-vit7b16-pretrain-sat493m) | Large vision transformer pretrained on satellite imagery for transferable visual representations and downstream remote sensing tasks. | Meta | Satellite imagery | Open / research |

---

## Embedding and Representation Models

| Resource | Description | Organization | Output | Access |
|---|---|---|---|---|
| [Google Satellite Embedding](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_SATELLITE_EMBEDDING_V1_ANNUAL) | Annual geospatial embedding product designed for downstream mapping, classification, retrieval, and spatial analysis. | Google | Geospatial embeddings | Google Earth Engine |
| [AlphaEarth Foundations](https://deepmind.google/discover/blog/alphaearth-foundations-helps-map-our-planet-in-unprecedented-detail/) | Foundation model framework for generating compact and reusable representations of Earth observation data. | Google DeepMind | Earth representation embeddings | Research / platform dependent |

---

## Benchmarks and Evaluation

| Resource | Description | Organization | Focus | Access |
|---|---|---|---|---|
| [GEO-Bench-2](https://github.com/The-AI-Alliance/GEO-Bench-2) | Benchmark suite for evaluating geospatial foundation models across multiple Earth observation tasks and datasets. | AI Alliance / collaborators | GeoAI foundation model evaluation | Open |

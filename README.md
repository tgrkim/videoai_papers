# Foundational Video AI Papers: A Curated Reading List

## Phase 1: 3D Convolutional Networks
* Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset (Carreira & Zisserman, 2017) - This paper established a dominant paradigm by "inflating" successful 2D image CNNs into 3D networks (I3D) for video and introduced the Kinetics dataset, which became the "ImageNet for video." (Code Repo)

## Phase 2: The Transformer Revolution
* Is Space-Time Attention All You Need for Video Understanding? (Bertasius, et al., 2021) - One of the first pure-transformer models for video, it introduced an efficient TimeSformer with "divided space-time attention" that became a foundational design pattern for video transformers. (Code Repo)

* ViViT: A Video Vision Transformer (Arnab, et al., 2021) - A parallel and influential work to TimeSformer, it systematically explored several effective strategies for factorizing spatial and temporal attention, providing a comprehensive toolkit for building video transformers. (Code Repo)

## Phase 3: Self-Supervised & Multimodal Pre-training
* Learning Transferable Visual Models From Natural Language Supervision (Radford, et al., 2021) - This is the CLIP paper. Although an image-text model, its contrastive learning approach enabled zero-shot video classification and set the stage for modern multimodal video understanding. (Code Repo)

* VideoMAE: Masked Autoencoders are Data-Efficient Learners for Self-Supervised Video Pre-Training (Tong, et al., 2022) - It successfully brought the "mask-and-predict" self-supervision strategy to video, showing that reconstructing heavily masked video tubelets is a highly effective way to pre-train strong video backbones without labels. (Code Repo)

* VATT: Transformers for Multimodal Self-Supervised Learning from Raw Video, Audio and Text (Akbari, et al., 2021) - A key paper in true multimodal learning, VATT demonstrated how to learn a powerful, unified representation from three modalities (video, audio, and text) simultaneously using a transformer with a contrastive objective.

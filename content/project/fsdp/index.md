---
title: Causal Coherence in Image Inpainting Integrating Causal Reasoning with VAEs for Image Restoration
summary: An example of using the in-built project page.
tags:
  - Deep Learning
  - Generative Models
  - Causal Inference
date: '2023-12-08T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:

url_code: 'https://github.com/SamJin98/CSDS600-DeepGenerativeModels-CausalInference'
url_pdf: 'project/fsdp/fsdp.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

The field of image inpainting has witnessed substantial growth, fueled by the need for advanced techniques in digital forensics, image restoration, and object removal. Traditional methods, however, often fall short in maintaining semantic coherence. Our research introduces a approach to image inpainting that integrates causal reasoning within a novel generative process, leveraging the strengths of Variational Autoencoders (VAEs) and Structural Causal Models (SCMs). We propose a model that adapts the Causal Layer of CausalVAE, enhanced by the structural elements of NVAE, to address three primary challenges: creating expressive neural networks, scaling up training for larger image sizes and groups, and maintaining training stability. This model focuses on the coherent reconstruction of missing or corrupted image regions through an understanding of causal relationships among features. Our approach not only enhances the semantic coherence and realism of inpainted images but also fosters interpretability in the latent space, paving the way for more reliable and comprehensible image restoration processes.
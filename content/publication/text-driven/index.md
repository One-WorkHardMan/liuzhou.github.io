---
title: 'Text-Driven Editing of Real Images using Diffusion Models with Error Corrector'
authors:
  - Zhou Liu
  - Yican Zhange
date: '2024-01-01'
publishDate: '2024-03-18T09:04:01.184462Z'
publication_types: ['paper-conference']
publication: In *IEEE International Joint Conference on Neural Networks*
publication_short: In *IJCNN*
abstract: Recently, text-guided diffusion models have shown remarkable effectiveness in image editing. However, there is still substantial room for improvement in editing real images outside the model's domain. Firstly, addressing OOD (out-of-domain) issues typically requires an extended training process to achieve knowledge embedding. Secondly, achieving high-fidelity edits in localized areas of real images while maintaining background consistency poses a considerable challenge. Therefore, we propose an innovative text-driven framework for real image editing that requires no masking or fine-tuning.Our method excels in several aspects. Firstly, we adopt an intuitive text-driven editing method without the need for additional information. Secondly, by freezing the diffusion model and training only an error corrector, we address the issue of cumulative error during the inversion process, preserving the rich prior knowledge of the diffusion model and avoiding catastrophic forgetting. Lastly, we introduce a single-step linear optimization algorithm to reduce the training cost in the early stages of editing.The experimental results indicate that our method surpasses other latest approaches on multiple metrics, and qualitative comparisons demonstrate outstanding fidelity and controllability in our editing results. This provides an efficient and powerful solution for text-driven real-image editing. You can find our code here.
tags: []

featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
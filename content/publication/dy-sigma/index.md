---
title: 'Dy-Sigma: A Generalized Accelerated Convergence Strategy for Diffusion Models'
authors:
  - Zhou Liu
  - Zheng Ye
  - Jing Liu
  - Jun Qin
date: '2024-01-01'
publishDate: '2024-03-18T09:04:01.184462Z'
publication_types: ['paper-conference']
publication: In *IEEE International Joint Conference on Neural Networks*
publication_short: In *IJCNN*
abstract: Recently, text-guided diffusion models have demonstrated outstanding performance in image generation, opening up new possibilities for specific tasks in various domains. Consequently, there is an urgent demand for training diffusion models tailored to specific tasks. The prolonged training duration and sluggish convergence of diffusion models present a formidable challenge when expediting the convergence process. Furthermore, there is still room for improvement in existing loss weight strategies. Firstly, the predefined loss weight strategy based on SNR (signal-to-noise ratio) transforms the diffusion process into a multi-objective optimization problem. However, reaching Pareto optimality under this strategy requires considerable time.
In contrast, the unconstrained optimization weight strategy can achieve lower objective values, but the fluctuating loss weights for each task result in unstable changes, leading to low training efficiency. In this paper, we propose a new loss weight strategy, Dy-Sigma, that combines the advantages of predefined and learnable loss weights, effectively balancing the gradient conflicts in multi-objective optimization. Experimental results demonstrate that our strategy significantly improves convergence speed, being \textbf{3.7 times} faster than the Const strategy.

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
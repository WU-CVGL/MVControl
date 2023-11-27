# MVControl

[**Paper**](https://arxiv.org/abs/2311.14494) | [**Project Page**](https://lizhiqi49.github.io/MVControl/)

Official implementation of MVControl: Adding Conditional Control to Multi-view Diffusion for Controllable Text-to-3D Generation

[Zhiqi Li](https://github.com/lizhiqi49), [Yiming Chen](https://github.com/codejoker-c), [Lingzhe Zhao](https://github.com/LingzheZhao), [Peidong Liu](https://ethliup.github.io/)

**The code will be released later.**

Abstract: *We introduce MVControl, a novel neural network architecture that enhances existing pre-trained multi-view 2D diffusion models by incorporating additional input conditions, e.g. edge maps. Our approach enables the generation of controllable multi-view images and view-consistent 3D content. To achieve controllable multi-view image generation, we leverage MVDream as our base model, and train a new neural network module as additional plugin for end-to-end task-specific condition learning. To precisely control the shapes and views of generated images, we innovatively propose a new conditioning mechanism that predicts an embedding encapsulating the input spatial and view conditions, which is then injected to the network globally. Once MVControl is trained, score-distillation (SDS) loss based optimization can be performed to generate 3D content, in which process we propose to use a hybrid diffusion prior. The hybrid prior relies on a pre-trained Stable-Diffusion network and our trained MVControl for additional guidance. Extensive experiments demonstrate that our method achieves robust generalization and enables the generation of controllable high-quality 3D content.*

<p align="center">
    <img src="assets/teaser.png">
</p>


## Method Overview
<p align="center">
    <img src="assets/diagram.png">
</p>



## BibTeX

```bibtex
@misc{li2023mvcontrol,
      title={MVControl: Adding Conditional Control to Multi-view Diffusion for Controllable Text-to-3D Generation}, 
      author={Zhiqi Li and Yiming Chen and Lingzhe Zhao and Peidong Liu},
      year={2023},
      eprint={2311.14494},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
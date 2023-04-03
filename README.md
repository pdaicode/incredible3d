# incredible3d
A curated list of awesome 3D rendering papers, inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).


<details open>
<summary>Dynamic Scenes</summary>

- [HexPlane: A Fast Representation for Dynamic Scenes](https://caoang327.github.io/HexPlane), Ang Cao, Justin Johnson, CVPR 2023 
- [K-Planes: Explicit Radiance Fields in Space, Time, and Appearance](https://sarafridov.github.io/K-Planes/), Sara Fridovich-Keil, et al., CVPR 2023
- [NeRFPlayer: A Streamable Dynamic Scene Representation with Decomposed Neural Radiance Fields](https://lsongx.github.io/projects/nerfplayer.html), Liangchen Song, et al., IEEE Transactions on Visualization and Computer Graphics, 2023
</details>


<details open>
<summary>Faster Inference</summary>

- [Learning Neural Transmittance for Efficient Rendering of Reflectance Fields](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html), Mohammad Shafiei et al., BMVC 2021 | [bibtex](./citations/NeuralTransmittance.txt)
- [Neural Sparse Voxel Fields](https://lingjie0206.github.io/papers/NSVF/), Liu et al., NeurIPS 2020 | [github](https://github.com/facebookresearch/NSVF) | [bibtex](./citations/NeRF-and-Beyond.bib#L135-L141) <!---Liu20neurips_sparse_nerf-->
- [AutoInt: Automatic Integration for Fast Neural Volume Rendering](http://www.computationalimaging.org/publications/automatic-integration/), Lindell et al., CVPR 2021 | [github](https://github.com/computational-imaging/automatic-integration) | [bibtex](./citations/NeRF-and-Beyond.bib#L127-L133) <!---Lindell20arxiv_AutoInt-->
- [DeRF: Decomposed Radiance Fields](https://arxiv.org/abs/2011.12490), Rebain et al. Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L222-L228) <!---Rebain20arxiv_derf-->
- [DONeRF: Towards Real-Time Rendering of Compact Neural Radiance Fields using Depth Oracle Networks](https://depthoraclenerf.github.io/), Neff et al., CGF 2021 | [github](https://github.com/facebookresearch/DONERF) | [bibtex](./citations/donerf.txt) <!---neff2021donerf-->
- [FastNeRF: High-Fidelity Neural Rendering at 200FPS](https://arxiv.org/abs/2103.10380), Garbin et al., Arxiv 2021 | [bibtex](./citations/fastnerf.txt) <!---Garbin21arxiv_FastNeRF-->
- [KiloNeRF: Speeding up Neural Radiance Fields with Thousands of Tiny MLPs ](https://arxiv.org/abs/2103.13744), Reiser et al., ICCV 2021 | [github](https://github.com/creiser/kilonerf) | [bibtex](./citations/kilonerf.txt) <!---reiser2021kilonerf-->
- [PlenOctrees for Real-time Rendering of Neural Radiance Fields](https://alexyu.net/plenoctrees/), Yu et al., Arxiv 2021 | [github](https://github.com/sxyu/volrend) | [bibtex](./citations/plenoctrees.txt) <!---yu2021plenoctrees-->
- [Mixture of Volumetric Primitives for Efficient Neural Rendering](https://arxiv.org/abs/2103.01954), Lombardi et al., SIGGRAPH 2021 | [bibtex](./citations/mixture.txt)
- [Light Field Networks: Neural Scene Representations with Single-Evaluation Rendering](https://vsitzmann.github.io/lfns/), Sitzmann et al., Arxiv 2021 | [github](https://github.com/vsitzmann/light-field-networks) | [bibtex](./citations/lfn.txt)
- [RT-NeRF: Real-Time On-Device Neural Radiance Fields Towards Immersive AR/VR Rendering](https://arxiv.org/abs/2212.01120), Li et al., ICCAD 2022 | [bibtex](./citations/rt-nerf.txt)
- [ENeRF: Efficient Neural Radiance Fields for Interactive Free-viewpoint Video](https://zju3dv.github.io/enerf/), Lin et al., SIGGRAPH 2022 | [github](https://github.com/zju3dv/ENeRF) | [bibtex](./citations/enerf.txt)
- [R2L: Distilling Neural Radiance Field to Neural Light Field for Efficient Novel View Synthesis](https://arxiv.org/abs/2203.17261), Wang et al., ECCV 2022 | [github](https://github.com/snap-research/R2L) | [bibtex](./citations/r2l.txt) <!---wang2022r2l-->
- [Real-Time Neural Light Field on Mobile Devices](https://arxiv.org/abs/2212.08057), Cao et al., Arxiv 2022 | [github](https://github.com/snap-research/MobileR2L) | [bibtext](./citations/r2l-mobile.txt) <!---cao2022mobiler2l-->
</details>


<details open>
<summary>Unconstrained Images</summary>

- [NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://nerf-w.github.io/), Martin-Brualla et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L152-L158) <!---MartinBrualla20arxiv_nerfw-->
- [Ha-NeRF:laughing:: Hallucinated Neural Radiance Fields in the Wild](https://rover-xingyu.github.io/Ha-NeRF/), Chen et al., CVPR 2022 | [github](https://github.com/rover-xingyu/Ha-NeRF) | [bibtex](./citations/Ha-NeRF.txt) <!---chen2021hallucinated-->
</details>


<details open>
<summary>Deformable</summary>

- [Deformable Neural Radiance Fields](https://nerfies.github.io/), Park et al., Arxiv 2020 | [github](https://github.com/google/nerfies) | [bibtex](./NeRF-and-Beyond.bib#L206-L212) <!---Park20arxiv_nerfies-->
- [D-NeRF: Neural Radiance Fields for Dynamic Scenes](https://www.albertpumarola.com/research/D-NeRF/index.html), Pumarola et al., CVPR 2021 | [github](https://github.com/albertpumarola/D-NeRF) | [bibtex](./NeRF-and-Beyond.bib#L214-L220) <!---Pumarola20arxiv_D_NeRF-->
- [Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://gafniguy.github.io/4D-Facial-Avatars/), Gafni et al., CVPR 2021 | [github](https://github.com/gafniguy/4D-Facial-Avatars) | [bibtex](./NeRF-and-Beyond.bib#L87-L93) <!---Gafni20arxiv_DNRF-->
- [Non-Rigid Neural Radiance Fields: Reconstruction and Novel View Synthesis of a Deforming Scene from Monocular Video](https://gvv.mpi-inf.mpg.de/projects/nonrigid_nerf/), Tretschk et al., Arxiv 2020 | [github](https://github.com/facebookresearch/nonrigid_nerf) | [bibtex](./NeRF-and-Beyond.bib#L283-L289) <!---Tretschk20arxiv_NR-NeRF-->
- [PVA: Pixel-aligned Volumetric Avatars](https://volumetric-avatars.github.io/), Raj et al., CVPR 2021 | [bibtex](./citations/pva.txt)
- [Neural Articulated Radiance Field](https://github.com/nogu-atsu/NARF), Noguchi et al., Arxiv 2021 | [github](https://github.com/nogu-atsu/NARF) | [bibtex](./citations/narf.txt)
- [CLA-NeRF: Category-Level Articulated Neural Radiance Field](https://arxiv.org/abs/2202.00181), Tseng et al., ICRA 2022 | [bibtex](./citations/cla-nerf.txt)
- [Animatable Neural Radiance Fields for Modeling Dynamic Human Bodies](https://zju3dv.github.io/animatable_nerf/), Peng et al., ICCV 2021 | [github](https://github.com/zju3dv/animatable_nerf) | [bibtex](citations/animatable_nerf.txt) <!---Peng21arxiv_animatable_nerf-->
- [A Higher-Dimensional Representation for Topologically Varying Neural Radiance Fields](https://hypernerf.github.io/), Park et al., Arxiv 2021 | [github](https://github.com/google/hypernerf) | [bibtex](./citations/hypernerf.txt)
- [Animatable Neural Radiance Fields from Monocular RGB Videos](https://arxiv.org/abs/2106.13629), Chen et al., Arxiv 2021 | [github](https://github.com/JanaldoChen/Anim-NeRF) | [bibtex](citations/anim_nerf.txt)
- [Neural Actor: Neural Free-view Synthesis of Human Actors with Pose Control](https://vcai.mpi-inf.mpg.de/projects/NeuralActor/), Liu et al., SIGGRAPH Asia 2021 | [bibtex](./citations/neuralactor.txt)
- [HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video](https://grail.cs.washington.edu/projects/humannerf/), Weng et al., CVPR 2022 | [github](https://github.com/chungyiweng/humannerf) | [bibtex](./citations/humannerf.txt)
</details>

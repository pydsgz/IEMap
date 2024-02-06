# IEMap
IE-Map: A novel in-vivo atlas and template of the human inner ear
<!--![](./data/fig_IEMap_3Drender.png)-->
<!--<img width="500" alt="" src="./data/fig_IEMap_3Drender.png">-->
<img width="500" alt="" src="https://zenodo.org/api/iiif/record:10625570:fig_IEMap_3Drender.png/full/!800,800/0/default.png">

## Publication and Citation
The atlas has been validated and published as an Open Access manuscript ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)) in Scientific Reports (Springer/Nature). If you make use of this material, please cite our work as follows:  

Ahmadi, SA., Raiser, T.M., Rühl, R.M. et al. IE-Map: a novel in-vivo atlas and template of the human inner ear. 
IE-Map: A novel in-vivo atlas template of the human inner ear <br>
Seyed-Ahmad Ahmadi, Theresa Raiser, Ria Maxine Ruehl, Virginia Flanagin, Peter zu Eulenburg <br>
Sci Rep 11, 3293 (2021). https://doi.org/10.1038/s41598-021-82716-0 <br>

## About
Brain atlases and templates are core tools in scientific research with increasing importance also in clinical applications. Advances in neuroimaging now allowed us to expand the atlas domain to the vestibular and auditory organ, the inner ear. In this study, we present IE-Map, an in-vivo template and atlas of the human labyrinth derived from multi-modal high-resolution magnetic resonance imaging (MRI) data, in a fully non-invasive manner without any contrast agent or radiation. We reconstructed a common template from 126 inner ears (63 normal subjects) and annotated it with 94 established landmarks and semi-automatic segmentations of all relevant macroscopic vestibular and auditory substructures. We validated the atlas by comparing MRI templates to a novel CT/micro-CT atlas, which we reconstructed from 21 publicly available post-mortem images of the bony labyrinth. Templates in MRI and micro-CT have a high overlap, and several key anatomical measures of the bony labyrinth in IE-Map are in line with micro-CT literature of the inner ear. A quantitative substructural analysis based on the new template, revealed a correlation of labyrinth parameters with total intracranial volume. No effects of gender or laterality were found. We provide the validated templates, atlas segmentations, surface meshes and landmark annotations as open-access material, to provide neuroscience researchers and clinicians in neurology, neurosurgery, and otorhinolaryngology with a widely applicable tool for computational neuro-otology.

## Download and installation
Please note: We have a limited download quota for the dataset on github. In case you receive a "quota exceeded" during cloning of the repo, please use this [temporary download link](https://drive.google.com/file/d/1Q57AhDwYPNELAUsVdbfaRQRphwFLhcOZ/view?usp=sharing). 

**New:** Alternatively, you can also download the dataset via Zenodo: https://zenodo.org/records/10625570

The T1/T2/CISS templates, segmentation labelmaps, surface models and landmarks are all available in the subdirectory /data. You can download a ZIP file of the whole repository, and unzip it locally in your system. The /data folder contains a 3D Slicer scene (IEMap_slicerScene_v_1_0.mrml). [3D Slicer](https://download.slicer.org/) is a cross-platform (Windows/Mac/Linux), open-source, and freely available software for medical image analysis and visualization. After installing and starting Slicer, unzip the data file and load the MRML scene file, e.g. via drag&drop into the Slicer user interface. Users without experience in 3D Slicer can follow a quick, [4-minute tutorial](https://www.slicer.org/wiki/Documentation/4.10/Training#Slicer4Minute_Tutorial) to learn how to navigate the template slices and the 3D scene.

## Acknowledgments
Some of the surface meshes in this repository (/data/ls_Hsapiens_*.vtk) were registered to our IE-Map template space. The source material was derived from David et al., Sci Rep, 2016 (published under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license). The material was modified for this work, by registration/deformation to our IE-Map template space. Please check and cite the original material published under:

David, R., Stoessel, A., Berthoz, A., Spoor, F. & Bennequin, D. Assessing morphology and function of the semicircular duct system: introducing new in-situ visualization and software toolbox. Sci. Rep. https://doi.org/10.1038/srep32772 (2016).

The CT/micro-CT templates in this repository were custom-built and reconstructed in our IE-Map template space. The original/unmodified source material was obtained from ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)):

Wimmer, W. et al. Human bony labyrinth dataset: co-registered CT and micro-CT images, surface models and anatomical landmarks. Data Brief 27, 104782. https://doi.org/10.1016/j.dib.2019.104782 (2019).

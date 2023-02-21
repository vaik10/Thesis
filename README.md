
# Super Resolution of lung Covid-19 CT images.

This jupyter notebook is part of my Thesis for M.tech. 

Acquisition of high quality CT images is difficult, because it requires exposing
patients to high doses of radiation .Super resolution algorithms can help in over-
coming this problem and obtain higher spatial resolution in CT images. Much
deep learning based architecture have been proposed in the literature to overcome
this problem. We perform the task of super resolution on a U-Net and study the
effects of 2 pre-processing methods which are scaling and z-score. The evaluation
strategy for the super resolution of CT images in the literature uses the Peak Sig-
nal to Noise Ratio (PSNR) and Structural Similarity (SSIM), however the results
are published for the entire image. This is not a good practice for the evaluation of
SR, we propose a novel region based similarity measurement practice and a lung
specific or region of interest based similarity measurement. We further bifurcate
the SSIM metric into it’s 3 component, i.e. luminance, contrast and structure, and
study the impact of super resolution on each of these components.


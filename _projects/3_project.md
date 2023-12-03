---
layout: page
title: computational radiology
description: Data-driven methods for radiology
img: assets/img/radiology_new.gif
importance: 3
category: medical applications
related_publications: sun2018radiomics, martinot2023differentiable, laousy2021deep, milecki2023medimpi, milecki2022contrastive, chassagnon2021ai, chassagnon2021elastic
---

Radiology could provide a non invasive way to address different diseases and treatments. Providing automatic tools for the analysis of radiology data could help on screening, diagnosis or even prognosis of radiologists during their clinical practice. Our team collaborates with the best clinicians to develop relavant methods for processing of radiology data. Currently, we have active collaborations with clinicians in [APHP hospitals](https://www.aphp.fr/), [Gustave Roussy](https://www.gustaveroussy.fr/en) and [Henry Dunant Hospital](https://www.dunant.gr/en/) towards this direction including [Hagnodice](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjWgMm9uPOCAxVEVKQEHRVEAaIQFnoECA0QAQ&url=https%3A%2F%2Fanr.fr%2FProject-ANR-21-CE45-0007&usg=AOvVaw31mm1Qvi4SfzbH09Ts0Rn_&opi=89978449), [Prism](https://prism.center/about-prism/), [Noesia](https://www.gustaveroussy.fr/fr/lancement-de-prism-centre-national-de-medecine-de-precision) and [Archimedes Unit](https://www.athenarc.gr/en/archimedes) projects.

---
### Towards cancer treatment

- In [Martinot et al. 2023](https://link.springer.com/chapter/10.1007/978-3-031-34048-2_37) we introduce a new class of Gamma index Passing Rate (GPR)-based loss functions for training of deep learning methods towards radiotherapy dose simulation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/martinot2023_ipmi.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Comparisons of different predictons of radiotherapy dose presented in IPMI 2023 [Martinot et al. 2023].
</div>

- In [Laousy et. al 2021](https://arxiv.org/pdf/2107.12800.pdf) we propose a deep reinforcement learning method for accurate localization of the third lumbar area (L3) CT slice towards sarcopenia prediction.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/laousy2021_miccai.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the method presented in MLMI workshop of MICCAI 2021 [Laousy et al. 2021].
</div>



- In [Sun et al. 2018](https://d1wqtxts1xzle7.cloudfront.net/59260291/sun201820190515-75809-48g3xd-libre.pdf?1557924258=&response-content-disposition=inline%3B+filename%3DA_radiomics_approach_to_assess_tumour_in.pdf&Expires=1701622583&Signature=SRAmdV7ClyyDuVyl2vI-92C97s0DxjzhbL~ICVrfQ1IpkS4p~UrwRSFsadV3Gw476DRPuh5IbIuocM7qmojQNx5mFVKlc6aVWOePGfduuSMxj6mKWVNAsFtEZLtCLIxvdDJaiq1wZAF0PIdQBBfctdO3XQK26zMDt41e8Ne79qZyKeaGIJIklSe6Pu3vqG6eAnloBIVXhWbKdS24msbo9VJmWE-Po3fodThTjZTmarxfvsQWY2uimL48GHjAkvlcU4ni-aIKjYwk~ViTWoj4EYyWfAZRnpx5t~nmHS5CaQrd3L~493ZAKZr53x2jMPZPm4XTX6soqYRda33BH-FzUg__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) we proposed one of the first radiomics signatures for CD8 cells and we indicated a promising way to predict the immune phenotype of tumours and to infer clinical outcomes for patients with cancer who had been treated with anti-PD-1 and PD-L1

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/sun2018.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Results for head and neck tumors presented in Lancet Oncology 2018 [Sun et al. 2018].
</div>

--- 

### Towards kidney transplantation monitoring

- In [Milecki et al, 2023](https://centralesupelec.hal.science/hal-04040697/document) ropose a framework that generates medical prompts using automatic textual data augmentations from LLMs. Our goal is to learn meaningful manifolds of renal transplant DCE MRI, interesting for the prognosis of the transplant or patient status.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/milcki2023_midl.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the method presented in MIDL 2023 [Milecki et al. 2023].
</div>

- In [Milecki et al. 2022](https://hal.science/hal-03738395/document) we propose a sequential architecture based on transformer encoders to predict the renal function 2-years post-transplantation, focusing on representation learning and missing data.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/milecki2022_miccai.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the method presented in MICCAI 2022 [Milecki et al. 2022].
</div>

---

### Towards lung interstitial diseases

- In [Chassagnon et al. 2021](https://www.sciencedirect.com/science/article/pii/S1361841520302243) we propose an automatic deep learning-based disease quantification using an ensemble of architectures, and a data-driven consensus for the staging and outcome prediction of the COVID-19 patients fusing imaging biomarkers with clinical and biological attributes. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chassagnon2022_media.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the method presented in Medical Image Analysis 2021 [Chassagnon et al. 2021].
</div>

- In [Chassagnon et al. 2021](https://pubs.rsna.org/doi/pdf/10.1148/radiol.2020200319) we develop a deep learning–based method to depict worsening of ILD based on lung shrinkage detection from elastic registration of chest CT scans in patients with systemic sclerosis.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chassagnon2021_radiology.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Results for ILD patients presented in Radiology 2021 [Chassagnon et al. 2021].
</div>



Word-list Multimodal Cortical Atlas (WMCA)
================

## Reference

Hesling, I., **Labache, L.**, Joliot, M., & Tzourio-Mazoyer, N. (2019).
Large-scale plurimodal networks common to listening to, producing and
reading word lists: an fMRI study combining task-induced activation and
intrinsic connectivity in 144 right-handers. Brain Structure and
Function, 224(9), 3075-3094. DOI:
[10.1007/s00429-019-01951-4](https://doi.org/10.1007/s00429-019-01951-4)

------------------------------------------------------------------------

## Background

**WMCA, Word-List Multimodal Cortical Atlas, is a new model of the
neural organization of phonological action–perception circuits.**

We aimed at identifying plurimodal large-scale networks common to
producing, listening to and reading word lists based on the combined
analyses of task-induced activation and resting-state intrinsic
connectivity.

In line with
[SENSAAS](https://github.com/loiclabache/SENSAAS_brainAtlas), **WMCA**
was developed from fMRI obtained during both task-induced and
resting-state acquisitions in 144 right-handed participants.

14 left regions and 7 right were identified as showing joint activation
and joint asymmetry during the three tasks of producing, listening to
and reading word lists. The temporal correlations at rest between these
21 regions made it possible to detect their belonging to 2 networks.
**Among these networks, one, *WORD-LIST_CORE* network that aggregated 14
motor, premotor and phonemic areas in the left hemisphere plus the right
Superior Temporal Sulcus that corresponded to the posterior human voice
area.**

<p align="center">
<img src="readme_files/WMCA_volume.gif" width="50%" height="50%" />
</p>

------------------------------------------------------------------------

## Data release

The `Atlas` folder contains 4 files:

-   `read_me_WMCA.rtf`: README file containing information about the
    atlas
-   `WMCA_MNI_ICBM_152_2mm.nii`: NIfTI file containing the 21 brain
    regions in the MNI space

<p align="center">
<img src="readme_files/WMCA.png" width="80%" height="80%" />
</p>

-   `WMCA_description.csv`: CSV file containing a full description of
    each areas. The first column (*Index*) correspond to the index of
    each region that is used in the NIfTI file. The second column
    (*ROI*) is the anatomical labels of each regions. The column
    *Network* corresponded to which of the 2 networks a region belongs.
    Finaly, the MNI coordinate (columns *Xmm*, *Ymm*, *Zmm*) of each
    regions centroid is provided.

-   `template_ANTs_80tvs_on_MNI.nii.gz`: brain template used to align
    the atlas on, provided in MNI stereotaxic space (MNI ICBM 152,
    Template sampling size of 2x2x2 mm3 voxels; bounding box, x = -90 to
    90 mm, y = -126 to 91 mm, z = -72 to 109 mm)

The 2 networks are briefly described below.

-   **WORD-LIST_CORE** included 18 essential sentence processing
    regions.
-   **WORD-LIST_CONTROL** aggregated areas acknowledged as involved in
    visual processing.

This above model posits that:

-   action and perception circuits are interdependent and organized in
    networks, among which a trace of the learning modality is still
    present in the brain;

-   the involvement of phonological action–perception circuits, such as
    the phonological working memory loop, in which articulatory gestures
    are the central motor units on which word perception, production and
    reading develop and act according to the motor theory of speech
    ([Liberman and Whalen
    2000](https://doi.org/10.1016/S1364-6613(00)01471-6)), as revealed
    by the recruitment of leftward frontal and precentral areas together
    with temporo-parietal areas;

-   the involvement of the left supramarginal (*SMG*) with the right
    superior temporal sulcus (*STS3*, pHVA), which is a prosodic
    integrative area, could reflect the intertwining between prosodic
    and phonemic information.

------------------------------------------------------------------------

## Other atlases that might interest you

-   SEntence Supramodal Areas AtlaS:
    [SENSAAS](https://github.com/loiclabache/SENSAAS_brainAtlas)
-   HAnd MOtor Area atlas:
    [HAMOTA](https://github.com/loiclabache/HAMOTA_brainAtlas)
-   Atlas of Lateralized visuospatial Attentional Networks:
    [ALANs](https://github.com/loiclabache/ALANs_brainAtlas)
-   Atlas of Intrinsic Connectivity of Homotopic Areas:
    [AICHA](https://www.gin.cnrs.fr/en/tools/aicha/)

------------------------------------------------------------------------

## Questions

Please contact me (Loïc Labache) as <loic.labache@yale.edu> and/or
<loic.labache@ensc.fr>

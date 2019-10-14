# Groundtruth of spliced images in dataset CASIA 1.0

* I also upload the original dataset since the owners' server is no longer avaiable.

Please notice that the authors made mistakes in naming the files. 
If you already downloaded the dataset, I recommend you to rename the tampered images using the commands in the excel file. 
Otherwise, you can use the modified version of dataset. 

Due to the lack of manual file, I write up here the naming convention:

## Authentic images: 800 images (8 categories, 100 images in each category).

Au_ani_0001.jpg
Au: Authentic
ani: animal category
Other categories: arc (architecture), art, cha (characters), nat (nature), pla (plants), sec, txt (texture)

## Tampering images

a. Spliced image

        Sp_D_CND_A_pla0005_pla0023_0281.jpg
* Sp: Splicing
* D: Different (means the tampered region was copied from the different image)
* Next 4 letters stand for the techniques they used to create the images. Unfortunately, I don't remember exactly.
* pla0005: the source image
* pla0023: the target image
* 0281: tampered image ID

b. Copy-move images

        Sp_S_CND_A_pla0016_pla0016_0196.jpg
* Sp: Tampering
* S: Same (means the tampered region was copied from the same image)
* And the rest is similar to case a.

If you use the groundtruth dataset for a scientific publication, please cite the following paper (https://res.mdpi.com/symmetry/symmetry-11-00083/article_deploy/symmetry-11-00083.pdf):

    @article{pham2019hybrid,
      title={Hybrid Image-Retrieval Method for Image-Splicing Validation},
      author={Pham, Nam Thanh and Lee, Jong-Weon and Kwon, Goo-Rak and Park, Chun-Su},
      journal={Symmetry},
      volume={11},
      number={1},
      pages={83},
      year={2019},
      publisher={Multidisciplinary Digital Publishing Institute}
    }

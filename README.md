# LPFF-Dataset

Download link: https://1drv.ms/u/s!AuIg2BWSs0cZaprO4fTFjy4Pk94?e=PvvFwr

We only released 1,000 images (re-aligned according to the EG3D function and the StyleGAN function, respectively). The complete dataset will be released after the acceptance of our paper.



| Path                     | Size   | Files | Format | Description                                                  |
| ------------------------ | ------ | ----- | ------ | ------------------------------------------------------------ |
| LPFF-Dataset             | 1.30GB | 2,001 |        | Main folder                                                  |
| ├ crop                   | 1.30GB | 2,000 |        | Final crop                                                   |
| │ ├ eg3d                 | 328MB  | 1,000 | PNG    | Aligned and cropped images at 512×512, according to [EG3D](https://github.com/NVlabs/eg3d) function. |
| │ ├ stylegan             | 0.98GB | 1,000 | PNG    | Aligned and cropped images at 1024×1024, according to [StyleGAN](https://github.com/NVlabs/ffhq-dataset) function. |
| └ camera_parameters.json | 398kb  | 1     | JSON   | Camera parameters.                                           |

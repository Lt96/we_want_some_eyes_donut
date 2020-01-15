# Galucoma Project
This project is a part of image processing class project at Mahidol University 
## Getting Started
This folder contains 3 subfolders
```
1. Final program: The final program with simple GUI
2. Individual code: This folder contain subfolders of each member codes
3. RAW_FUNDUS_INPUT: This folder contains raw retina fundus images
```
### Installing
The final program requires `numpy`, `pandas`, `xlrd`, `glob`, `cv2`, `matplotlib`,
`pywt`, `scipy`, `tkinter`, `PIL`, `math`,and `skimage`

Some individual codes require more modules than this.

Some individual codes requires RAW_FUNDUS_INPUT folder in their directory.
### Running
1. Open Final program folder
2. Run Glaucoma_CDR_finder_program.ipynb
3. Execute every cells
4. The program GUI will pop up, then browse and select fundus image in RAW_FUNDUS_INPUT
5. The result will display
## Built with
* Jupyter Notebook
* Spyder
* VScode
* Matlab
## Known bugs
* OD localization tends to error when too much light leaks through the fundus camera
* If the input image size is changed, the localize program will crash
* If OD center is too clsoe to the image edge that cause size of ROI too change,
the cup segmentation program will crash.
* Cup segmentation program still has significant error which also cause error to CDR result.
## Authors
- **���õԾ��� ����Է��** - *initial work*
- **���ɰ� �٭�٧���õ�** - *initial work*
- **��ҹ��� ���դ����آ** - *initial work*
- **�ǹҡ� ����ҳ��ѵ�** - *initial work*
- **���Ūҵ� ���Һѵ�** - *initial work*
- **��óѰ ����Ҹ��Թ** - *initial work*
- **��ɮ쾧�� ������** - *initial work*
- **�Է�ԡ� �ح�����ҡ�** - *initial work*
- **���ح �����ѡ�** - *initial work*
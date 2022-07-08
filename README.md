# fractal-compressor
This is my image compressor implementing the fractal compression method. It includes encoder and decoder, which uses quadro-tree technic and accomplish 5 levels of coding quality. The images are compared by psnr
# Building
Create anaconda enviroment with `python=3.7` and install `requirements.txt`
```shell
  conda create --name fractal python=3.7
  conda activate fractal
  pip install -r requirements.txt
```
You can choose a different environment name instead of `fractal`.
# Testing
You can run code in `jupyter notebook`. Then you need to import your kernel environment in notebook and choose this kernel `fractal`
```shell
  conda install -c anaconda ipykernel
  python -m ipykernel install --user --name=fractal
```
Or you can build project and run local testing
```shell
  python test_templates/compose.py
  python fractal-compression.py
```
All images from the `test_files` folder with all quality parameters will be tested and the results will be saved to the `results.csv` file.
# Image evolution

# Test results
All tests were completed in less than  minutes

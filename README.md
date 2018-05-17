## Cloud masking of Sentinel 2 using Google Earth Engine

Cloud, and shadow, masking of Sentinel 2 images using Google Earth Engine Python API. Refactored from javascipt posted in the forum in this thread: [Sentinel 2 cloud masking](https://groups.google.com/forum/#!searchin/google-earth-engine-developers/cloud$20masking%7Csort:relevance/google-earth-engine-developers/i63DS-Dg8Sg/Kc0knF9BBgAJ).

### Dependencies

* [Google Earth Engine Python API](https://developers.google.com/earth-engine/python_install)
* [Ipython](https://ipython.org/install.html)

### Usage

Authenticate Earth Engine (if necessary)

`earthengine authenticate`

Run the jupyter notebook
```
git clone https://github.com/samsammurphy/cloud-masking-sentinel2.git
cd cloud-masking-sentinel2
jupyter-notebook cloud-masking-sentinel2.ipynb
```

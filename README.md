# Predict-Decline
Feature selection on vertex-wise CT measures to predict cognitive decline

Feature selection methods:
- Automated Anatomical Labeling (baseline)
- Principal Component Analysis
- Recursive Feature Elimination
- Regularized Logistic Regression (Moradi et al., 2015)
- Hierarchical Clustering Analysis

Machine learning classification methods:
- Artificial Neural Network
- Logistic Regression
- Random Forests
- Support Vector Machines
- Longitudinal Siamese Network (Bhagwat et al., 2018)

Set up module dependencies: \n
```module load anaconda/5.1.0-python3```

List of packages in conda virtual machine:
```
Name                    Version                   Build  Channel
_ipyw_jlab_nb_ext_conf    0.1.0            py36he11e457_0  
alabaster                 0.7.10           py36h306e16b_0  
anaconda                  5.1.0                    py36_2  
anaconda-client           1.6.9                    py36_0  
anaconda-navigator        1.7.0                    py36_0  
anaconda-project          0.8.2            py36h44fb852_0  
apipkg                    1.5                      py36_0  
asn1crypto                0.24.0                   py36_0  
astroid                   1.6.1                    py36_0  
astropy                   2.0.3            py36h14c3975_0  
attrs                     17.4.0                   py36_0  
babel                     2.5.3                    py36_0  
backports                 1.0              py36hfa02d7e_1  
backports.shutil_get_terminal_size 1.0.0            py36hfea85ff_2  
beautifulsoup4            4.6.0            py36h49b8c8c_1  
bitarray                  0.8.1            py36h14c3975_1  
bkcharts                  0.2              py36h735825a_0  
blas                      1.0                         mkl  
blaze                     0.11.3           py36h4e06776_0  
bleach                    2.1.2                    py36_0  
bokeh                     0.12.13          py36h2f9c1c0_0  
boto                      2.48.0           py36h6e4cd66_1  
bottleneck                1.2.1            py36haac1ea0_0  
bzip2                     1.0.6                h9a117a8_4  
ca-certificates           2018.03.07                    0  
cairo                     1.14.12              h77bcde2_0  
certifi                   2018.10.15               py36_0  
cffi                      1.11.4           py36h9745a5d_0  
chardet                   3.0.4            py36h0f667ec_1  
click                     6.7              py36h5253387_0  
cloudpickle               0.5.2                    py36_1  
clyent                    1.2.2            py36h7e57e65_1  
colorama                  0.3.9            py36h489cec4_0  
conda                     4.5.11                   py36_0  
conda-build               3.4.1                    py36_0  
conda-env                 2.6.0                h36134e3_1  
conda-verify              2.0.0            py36h98955d8_0  
configargparse            0.13.0                   py36_0  
contextlib2               0.5.5            py36h6c84a62_0  
cryptography              2.1.4            py36hd09be54_0  
curl                      7.58.0               h84994c4_0  
cvxopt                    1.2.0            py36h9e0dedd_0  
cycler                    0.10.0           py36h93f1223_0  
cython                    0.27.3           py36h1860423_0  
cytoolz                   0.9.0            py36h14c3975_0  
dask                      0.16.1                   py36_0  
dask-core                 0.16.1                   py36_0  
datashape                 0.5.4            py36h3ad6b5c_0  
dbus                      1.12.2               hc3f9b76_1  
decorator                 4.3.0                    py36_0  
dipy                      0.14.0           py36h7eb728f_1    conda-forge
distributed               1.20.2                   py36_0  
docutils                  0.14             py36hb0f60f5_0  
entrypoints               0.2.3            py36h1aec115_2  
et_xmlfile                1.0.1            py36hd6bccc3_0  
execnet                   1.5.0                    py36_0  
expat                     2.2.5                he0dffb1_0  
fastcache                 1.0.2            py36h14c3975_2  
filelock                  2.0.13           py36h646ffb5_0  
flask                     0.12.2           py36hb24657c_0  
flask-cors                3.0.3            py36h2d857d3_0  
fontconfig                2.12.4               h88586e7_1  
freetype                  2.8                  hab7d2ae_1  
funcsigs                  1.0.2                    py36_0  
future                    0.17.1                   py36_0  
get_terminal_size         1.0.0                haa9412d_0  
gevent                    1.2.2            py36h2fe25dc_0  
glib                      2.53.6               h5d9569c_2  
glob2                     0.6              py36he249c77_0  
glpk                      4.65                 h3ceedfd_2  
gmp                       6.1.2                h6c8ec71_1  
gmpy2                     2.0.8            py36hc8893dd_2  
graphite2                 1.3.10               hf63cedd_1  
greenlet                  0.4.12           py36h2d503a6_0  
gsl                       2.4                  h14c3975_4  
gst-plugins-base          1.12.4               h33fb286_0  
gstreamer                 1.12.4               hb53b477_0  
h5py                      2.7.1            py36h3585f63_0  
harfbuzz                  1.7.4                hc5b324e_0  
hdf5                      1.10.1               h9caa474_1  
heapdict                  1.0.0                    py36_2  
html5lib                  1.0.1            py36h2f9c1c0_0  
icu                       58.2                 h9c2bf20_1  
idna                      2.6              py36h82fb2a8_1  
imageio                   2.2.0            py36he555465_0  
imagesize                 0.7.1            py36h52d8127_0  
intel-openmp              2018.0.0             hc7b2577_8  
ipykernel                 4.8.0                    py36_0  
ipython                   6.2.1            py36h88c514a_1  
ipython_genutils          0.2.0            py36hb52b0d5_0  
ipywidgets                7.1.1                    py36_0  
isodate                   0.6.0                    py36_0  
isort                     4.2.15           py36had401c0_0  
itsdangerous              0.24             py36h93cc618_1  
jbig                      2.1                  hdba287a_0  
jdcal                     1.3              py36h4c697fb_0  
jedi                      0.11.1                   py36_0  
jinja2                    2.10             py36ha16c418_0  
jpeg                      9b                   h024ee3a_2  
jsonschema                2.6.0            py36h006f8b5_0  
jupyter                   1.0.0                    py36_4  
jupyter_client            5.2.2                    py36_0  
jupyter_console           5.2.0            py36he59e554_1  
jupyter_core              4.4.0            py36h7c827e3_0  
jupyterlab                0.31.5                   py36_0  
jupyterlab_launcher       0.10.2                   py36_0  
keepalive                 0.5                        py_1    conda-forge
lazy-object-proxy         1.3.1            py36h10fcdad_0  
libcurl                   7.58.0               h1ad7b7a_0  
libedit                   3.1                  heed3624_0  
libffi                    3.2.1                hd88cf55_4  
libgcc-ng                 7.2.0                h7cc24e2_2  
libgfortran-ng            7.2.0                h9f7466a_2  
libpng                    1.6.34               hb9fc6fc_0  
libsodium                 1.0.15               hf101ebd_0  
libssh2                   1.8.0                h9cfc8f7_4  
libstdcxx-ng              7.2.0                h7a57d05_2  
libtiff                   4.0.9                h28f6b97_0  
libtool                   2.4.6                h544aabb_3  
libxcb                    1.12                 hcd93eb1_4  
libxml2                   2.9.7                h26e45fe_0  
libxslt                   1.1.32               h1312cb7_0  
llvmlite                  0.21.0           py36ha241eea_0  
locket                    0.2.0            py36h787c0ad_1  
lxml                      4.1.1            py36hf71bdeb_1  
lzo                       2.10                 h49e0be7_2  
markupsafe                1.0              py36hd9260cd_1  
matplotlib                2.1.2            py36h0e671d2_0  
mccabe                    0.6.1            py36h5ad9710_1  
metis                     5.1.0                hf484d3e_4  
mistune                   0.8.3                    py36_0  
mkl                       2019.0                      118  
mkl-service               1.1.2            py36h17a0993_4  
mock                      2.0.0                    py36_0  
mpc                       1.0.3                hec55b23_5  
mpfr                      3.1.5                h11a74b3_2  
mpmath                    1.0.0            py36hfeacd6b_2  
msgpack-python            0.5.6            py36h6bb024c_1  
multipledispatch          0.4.9            py36h41da3fb_0  
navigator-updater         0.1.0            py36h14770f7_0  
nbconvert                 5.3.1            py36hb41ffb7_0  
nbformat                  4.4.0            py36h31c9010_0  
ncurses                   6.0                  h9df7e31_2  
networkx                  2.2                      py36_1  
nibabel                   2.3.1              pyh24bf2e0_0    conda-forge
nilearn                   0.4.2              pyh24bf2e0_0    conda-forge
nipype                    1.1.5                    py36_0    conda-forge
nitime                    0.7              py36h7eb728f_2    conda-forge
nltk                      3.2.5            py36h7532b22_0  
nose                      1.3.7            py36hcdf7029_2  
notebook                  5.4.0                    py36_0  
numba                     0.36.2          np114py36hc6662d5_0  
numexpr                   2.6.4            py36hc4a3f9a_0  
numpy                     1.14.2           py36hdbf6ddf_0  
numpydoc                  0.7.0            py36h18f165f_0  
odo                       0.5.1            py36h90ed295_0  
olefile                   0.45.1                   py36_0  
openpyxl                  2.4.10                   py36_0  
openssl                   1.0.2p               h14c3975_0  
ordered-set               3.0.2                      py_0    conda-forge
packaging                 16.8             py36ha668100_1  
pandas                    0.23.4           py36h04863e7_0  
pandoc                    1.19.2.1             hea2e7c5_1  
pandocfilters             1.4.2            py36ha6701b7_1  
pango                     1.41.0               hd475d92_0  
parso                     0.1.1            py36h35f843b_0  
partd                     0.3.8            py36h36fd896_0  
patchelf                  0.9                  hf79760b_2  
path.py                   10.5             py36h55ceabb_0  
pathlib2                  2.3.0            py36h49efa8e_0  
patsy                     0.5.0                    py36_0  
pbr                       5.1.0                    py36_0  
pcre                      8.41                 hc27e229_1  
pep8                      1.7.1                    py36_0  
pexpect                   4.3.1                    py36_0  
pickleshare               0.7.4            py36h63277f8_0  
pillow                    5.0.0            py36h3deb7b8_0  
pip                       9.0.1            py36h6c6f9ce_4  
pixman                    0.34.0               hceecf20_3  
pkginfo                   1.4.1            py36h215d178_1  
pluggy                    0.6.0            py36hb689045_0  
ply                       3.10             py36hed35086_0  
prompt_toolkit            1.0.15           py36h17d85b1_0  
prov                      1.5.0                    py36_0    conda-forge
psutil                    5.4.3            py36h14c3975_0  
ptyprocess                0.5.2            py36h69acd42_0  
py                        1.5.2            py36h29bf505_0  
pycodestyle               2.3.1            py36hf609f19_0  
pycosat                   0.6.3            py36h0a5515d_0  
pycparser                 2.18             py36hf9f622e_1  
pycrypto                  2.6.1            py36h14c3975_7  
pycurl                    7.43.0.1         py36hb7f436b_0  
pydicom                   1.2.0                      py_0    conda-forge
pydotplus                 2.0.2                    py36_1  
pyflakes                  1.6.0            py36h7bd6a15_0  
pygments                  2.2.0            py36h0d3125c_0  
pylint                    1.8.2                    py36_0  
pyodbc                    4.0.22           py36hf484d3e_0  
pyopenssl                 17.5.0           py36h20ba746_0  
pyparsing                 2.2.0            py36hee85983_1  
pyqt                      5.6.0            py36h0386399_5  
pyro4                     4.74                       py_0    conda-forge
pysocks                   1.6.7            py36hd97a5b1_1  
pytables                  3.4.2            py36h3b5282a_2  
pytest                    3.3.2                    py36_0  
pytest-forked             0.2                      py36_0  
pytest-xdist              1.24.0                   py36_0  
python                    3.6.4                hc3d631a_1  
python-dateutil           2.6.1            py36h88d3b88_1  
pytz                      2017.3           py36h63b9c63_0  
pywavelets                0.5.2            py36he602eb0_0  
pyyaml                    3.12             py36hafb9ca4_1  
pyzmq                     16.0.3           py36he2533c7_0  
qt                        5.6.2               h974d657_12  
qtawesome                 0.4.4            py36h609ed8c_0  
qtconsole                 4.3.1            py36h8f73b5b_0  
qtpy                      1.3.1            py36h3691cc8_0  
rdflib                    4.2.2                 py36_1000    conda-forge
readline                  7.0                  ha6073c6_4  
requests                  2.18.4           py36he2e5f8d_1  
rope                      0.10.7           py36h147e2ec_0  
ruamel_yaml               0.15.35          py36h14c3975_1  
scikit-image              0.13.1           py36h14c3975_1  
scikit-learn              0.19.1           py36h7aa7ec6_0  
scipy                     1.0.0            py36hbf646e7_0  
seaborn                   0.8.1            py36hfad7ec4_0  
send2trash                1.4.2                    py36_0  
serpent                   1.27                       py_0    conda-forge
setuptools                38.4.0                   py36_0  
simplegeneric             0.8.1                    py36_2  
simpleitk                 1.1.0            py36hf484d3e_0    simpleitk
simplejson                3.16.0           py36h14c3975_0  
singledispatch            3.4.0.3          py36h7a266c3_0  
sip                       4.18.1           py36h51ed4ed_2  
six                       1.11.0           py36h372c433_1  
snowballstemmer           1.2.1            py36h6febd40_0  
sortedcollections         0.5.3            py36h3c761f9_0  
sortedcontainers          1.5.9                    py36_0  
sparqlwrapper             1.8.2                 py36_1000    conda-forge
sphinx                    1.6.6                    py36_0  
sphinxcontrib             1.0              py36h6d0f590_1  
sphinxcontrib-websupport  1.0.1            py36hb5cb234_1  
spyder                    3.2.6                    py36_0  
sqlalchemy                1.2.1            py36h14c3975_0  
sqlite                    3.22.0               h1bed415_0  
statsmodels               0.8.0            py36h8533d0b_0  
suitesparse               5.2.0                h171a5a3_0  
sympy                     1.1.1            py36hc6d1c1c_0  
tbb                       2018.0.4             h6bb024c_1  
tblib                     1.3.2            py36h34cf8b6_0  
terminado                 0.8.1                    py36_1  
testpath                  0.3.1            py36h8cadb63_0  
tk                        8.6.7                hc745277_3  
toolz                     0.9.0                    py36_0  
tornado                   4.5.3                    py36_0  
traitlets                 4.3.2            py36h674d592_0  
traits                    4.6.0            py36h14c3975_2  
typing                    3.6.2            py36h7da032a_0  
unicodecsv                0.14.1           py36ha668878_0  
unixodbc                  2.3.4                hc36303a_1  
urllib3                   1.22             py36hbe7ace6_0  
wcwidth                   0.1.7            py36hdf4376a_0  
webencodings              0.5.1            py36h800622e_1  
werkzeug                  0.14.1                   py36_0  
wheel                     0.30.0           py36hfd4bba0_1  
widgetsnbextension        3.1.0                    py36_0  
wrapt                     1.10.11          py36h28b7045_0  
xlrd                      1.1.0            py36h1db9f0c_1  
xlsxwriter                1.0.2            py36h3de1aca_0  
xlwt                      1.3.0            py36h7b00a1f_0  
xvfbwrapper               0.2.9                 py36_1000    conda-forge
xz                        5.2.3                h55aa19d_2  
yaml                      0.1.7                had09818_2  
zeromq                    4.2.2                hbedb6e5_2  
zict                      0.1.3            py36h3a3bf81_0  
zlib                      1.2.11               ha838bed_2
```

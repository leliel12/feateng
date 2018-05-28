virtualenv -P python3 ~/feateng
source ~/feateng/bin/active

pip3 install jupyter
pip3 install scikit-learn
pip3 install lxml
pip3 install numpy
pip3 install scipy
pip3 install matplotlib
pip3 install stemming
pip3 install gensim

jupyter notebook --no-browser .

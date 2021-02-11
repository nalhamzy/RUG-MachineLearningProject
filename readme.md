<h1 class="code-line" data-line-start=0 data-line-end=1><a id="ML_Project_0"></a>ML Project</h1>
<p class="has-line-data" data-line-start="3" data-line-end="4">The file ml_model.ipynb contains the implementation of all models and helper functions.</p>
<ul>
<li class="has-line-data" data-line-start="5" data-line-end="6">fitLogisticRegression: creates and fits a logistic regression model</li>
<li class="has-line-data" data-line-start="6" data-line-end="7">create_ResNet50_model : creates a resnet50 model with appropriate input/output dimentions.</li>
<li class="has-line-data" data-line-start="7" data-line-end="9">create_best_model: creates a 2-layer convolutional neural network .</li>
</ul>
<h1 class="code-line" data-line-start=9 data-line-end=10><a id="Dataset_9"></a>Dataset</h1>
<ul>
<li class="has-line-data" data-line-start="11" data-line-end="12">The folder img contains the resized dataset (128 by 128) pixels.</li>
<li class="has-line-data" data-line-start="12" data-line-end="13">The original dataset is available at the following url: <a href="https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia">https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia</a></li>
<li class="has-line-data" data-line-start="13" data-line-end="14">To use different location please change the global variable IMG_LOC which holds the current image path.</li>
</ul>
<h3 class="code-line" data-line-start=16 data-line-end=17><a id="Installation_16"></a>Installation</h3>
<p class="has-line-data" data-line-start="18" data-line-end="22">The code is tested on python 3.7<br>
and requires tensor flow 2.3.1<br>
!pip3 install opencv-python --user<br>
!pip3 install tensorflow --user</p>
<h3 class="code-line" data-line-start=22 data-line-end=23><a id="RUN_22"></a>RUN</h3>
<p class="has-line-data" data-line-start="23" data-line-end="24">python3 ml_model.py</p>
<h2 class="code-line" data-line-start=30 data-line-end=32><a id="License_30"></a>License</h2>
<p class="has-line-data" data-line-start="33" data-line-end="34">MIT</p>
</body></html>

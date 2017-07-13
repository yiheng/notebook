# OReillyAIConf

In this tutorial, we will give a comprehensive introduction of BigDL and run several hand-on exercises. To be able to run these BigDL hand-on exercises, the attendees need to setup an environment on your laptops.

Please note we will provide sandbox environments on our servers during the tutorial. So no worry if you havn't setup your own local environment. As the sandbox servers are shared, we still prefer that you have your own environment.

## Slides
https://github.com/yiheng/OReillyAIConf/blob/master/strata-2017-training.pdf

## Setup Local Environment

### Docker
* Step 1, sudo docker run -it --name=bigdltest --net=host intelanalytics/bigdl:0.1.1-spark2.1.0-u14.04-v1 bash
* Step 2, ./start-notebook
* Step 3, http://[host-ip]:8888

### For mac users
* Step 1, install some pre-requirements by following this [page](https://github.com/intel-analytics/BigDL-Tutorials/blob/master/SetupMac.md)
* Step 2, download BigDL from [this](https://drive.google.com/file/d/0B7WbKES2D6AxTDJaaUdlRVFRMFU/view?usp=sharing)
* Step 3, start a local jupyter server by following [this](https://github.com/intel-analytics/BigDL-Tutorials#start-jupyter-server)

### For linux users
* Step 1, install some pre-requirements by following this [page](https://github.com/intel-analytics/BigDL-Tutorials/blob/master/SetupLinux.md)
* Step 2, download BigDL from [this](https://repo1.maven.org/maven2/com/intel/analytics/bigdl/dist-spark-2.1.0-scala-2.11.8-linux64/0.1.1/dist-spark-2.1.0-scala-2.11.8-linux64-0.1.1-dist.zip)
* Step 3, start a local jupyter server by following [this](https://github.com/intel-analytics/BigDL-Tutorials#start-jupyter-server)

### For windows users
BigDL hasn't support windows yet. So please use the sandbox environment on our servers

## Sandbox environment

* Step 1, please choose one of these servers
1. http://54.169.215.11:8888
2. http://54.169.164.129:8888
3. http://54.169.152.149:8888
4. http://52.77.233.103:8888

* Step 2, please open the URL, then "New" -> Folder
![](https://github.com/yiheng/OReillyAIConf/raw/master/step2.PNG)

* Step 3, select the folder, then "Rename"
![](https://github.com/yiheng/OReillyAIConf/raw/master/step3.PNG)

* Step 4, input a unique id, say your name, click the "rename" button
![](https://github.com/yiheng/OReillyAIConf/raw/master/step4.PNG)

* Step 5, go into your folder, then "New" -> "Python 2"
![](https://github.com/yiheng/OReillyAIConf/raw/master/step5.PNG)

* Step 6, in the new opened page, write your code in the notebook


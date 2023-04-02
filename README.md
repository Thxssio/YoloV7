
<p align="center">
<img src="https://raw.githubusercontent.com/goktug97/PyYOLO/master/pyyologo.png" alt="yolo" height="200" Weight
="auto">
</p>

  - Primeiro clone o git oficial do yolo 

``` 
  git clone https://github.com/WongKinYiu/yolov7.git
  
```
#
 - Entre na pasta onde está o yolo 

```
  cd yolov7
  
```
#
 - Instale os pacotes necessarios

```
  pip install -r requirements.txt
  
```
#

- Detectando objetos

```
  python detect.py --weights yolov7-e6e.pt --source ./man_cafe.jpg
  python detect.py --source inference-data/busy_street.mp4 --weights yolov7.pt --name video_1 --view-img
  
```

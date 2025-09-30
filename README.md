# pyppbox-demo

## 1. Project Pikachu

***Project Pikachu*** is a showcase of using [***pyppbox***](https://github.com/rathaumons/pyppbox) in real-life. The system can track and re-identify specific/certain people through normal 2D cameras without having to spend much effort on the calibration, etc.

https://github.com/rathaumons/pyppbox-demo/assets/60795657/4c4b7865-ab22-4548-ad0c-d157635ae99c

Main modules:
- Detector: YOLO_Classic (v4)
- Tracker: SORT
- ReIDer: Torchreid (OSNet-AIN)

Check [supported modules](https://rathaumons.github.io/pyppbox/pyppbox/modules.html) for more details.

Watch on YouTube: https://youtu.be/jFPDbgPJBds

## 2. People Grouping: DABPG + DeepMVPG

[DABPG]() & [DeepMVPG](), state-of-art people grouping methods, were built on top of [***pyppbox***](https://github.com/rathaumons/pyppbox), thanks to [***pyppbox***](https://github.com/rathaumons/pyppbox) with its robust [person object class](https://rathaumons.github.io/pyppbox/pyppbox/utils.html#pyppbox.utils.persontools.Person) which offers a solid infrastructure for easily managing detected individuals. 

The demos below rely on the provided ground-truth ([Converted to pyppbox format](https://rathaumons.github.io/pyppbox/pyppbox/utils.html#module-pyppbox.utils.mot2pyppbox)) of [MOT dataset](https://motchallenge.net/) for people detection and tracking. The personal rings of individuals in the same group share the same color.

MOT-16-04:
<video src="https://github.com/user-attachments/assets/4dc32eb2-caae-4dc8-82b5-0a36ab3fa202"></video>

MOT-20-03:
<video src="https://github.com/user-attachments/assets/1079b8fc-ad31-4549-bb57-2cc1a9beb359"></video>

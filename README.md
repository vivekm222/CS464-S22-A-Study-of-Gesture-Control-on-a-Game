# Mario Gesture Control game

## Prerequisites

Install the following libraries:
- tensorflow
- cv2
- nes-py
- gym-super-mario-bros
- gym-chrome-dino
- numpy
- gym

Libraries such as [nes-py](https://pypi.org/project/nes-py/), gym-super-mario-bros, gym-chrome-dino help us setting the Mario game with some customizable controls.

Libraries such as tensorflow, cv2, numpy help to work with recogznizing the hand gestures. A pretrained model is fetched from Kaggle which returns the location of hand with respect to camera and wether the fist is closed or open state. Using these inputs, we've customized 6 game controls - Jump left, run left(fist-open , jump, stay, jump right, run right.

The loop runs infinitely and two controllers are initialized. One controller to control Super Mario game and the other controller to read in gesture from the user.

## Working of the program

To run the program, we need to run `python mario.py`

It takes a bunch of time to load all the modules and render the game. The program might throw some warnings regarding availability of GPUs and it can be neglected.

## Further Applcations

This application can be further applied to a wide variety of games such as playing Virtual Tennis or Virtual FPS shooter games, etc. Although the confidence of the machine learning model has to be improved a lot to achieve the applications mentioned above but this is a start.
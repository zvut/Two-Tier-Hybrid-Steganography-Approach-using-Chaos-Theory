# Two-Tier-Hybrid-Steganography-Approach-using-Chaos-Theory.

The proposed system is a 2 Tier Security System, in which first the messages is encoded in image and then the image is shuffled to provide a higher level of security of images. Eavesdrop cannot cryptanalysis the cipher image. Here, the security relies on a secret key along with the image encryption technique. Chaos is known for randomness, so it is highly secured. Confusion has been done by pixel movement form actual position to a new position and diffusion has been done through byte sequence generated through Henon map. So both the processes of increasing confusion and diffusion resulted in increasing the security of cryptosystem.

## Built In 

Jupyter Notebook



```bash
pip install jupyterlab
```

## Methodology  
First LSB method is used to hide data within image.  
Then for encrypting image we have shuffled image's pixels using chaos theory, to create a noise image.  
Chaotic systems are a simple sub-type of nonlinear dynamical systems. They may contain very few interacting parts and these may follow very simple rules, but these systems all have a very sensitive dependence on their initial conditions. Despite their deterministic simplicity, over time these systems can produce totally unpredictable and wildly divergent behavior.  
There are various ways to implement Chaos Theory. We have used the Henon Map.  
Given initial conditions (x0,y0), a henon map is given by the following equations:  
(Xn+1) = (Yn) + 1 − a.(Xn)^2  
(Yn+1) = b * (Xn)  
Classical Henon map have values of a = 1.4 and b = 0.3. For the classical values the Henon map is chaotic. For other values of a and b the map may be chaotic, intermittent, or converge to a periodic orbit.
## Usage

```python
from PIL import Image
import numpy as np
from matplotlib.pyplot import imshow
import cv2
%run ./ENCODE.ipynb # returns Encrypted Image
%run ./DECODE.ipynb # returns Message that is encrypted before.
%run ./Comparision.ipynb # compare orignal and fianl image on basis of pixel intensity.

```

## OUTPUT

ENCODING:  
![](https://github.com/MayankShekhar-MrMaaK/Two-Tier-Hybrid-Steganography-Approach-using-Chaos-Theory./blob/master/crenc.png)  
DECODING:  
![](https://github.com/MayankShekhar-MrMaaK/Two-Tier-Hybrid-Steganography-Approach-using-Chaos-Theory./blob/master/b5.png)  


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MAAK](https://mrmaak.tech/)

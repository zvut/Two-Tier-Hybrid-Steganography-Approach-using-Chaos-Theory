# Two-Tier-Hybrid-Steganography-Approach-using-Chaos-Theory.

The proposed system is a 2 Tier Security System, in which first the messages is encoded in image and then the image is shuffled to provide a higher level of security of images. Eavesdrop cannot cryptanalysis the cipher image. Here, the security relies on a secret key along with the image encryption technique. Chaos is known for randomness, so it is highly secured. Confusion has been done by pixel movement form actual position to a new position and diffusion has been done through byte sequence generated through Henon map. So both the processes of increasing confusion and diffusion resulted in increasing the security of cryptosystem.

## Built In 

Jupyter Notebook



```bash
pip install jupyterlab
```

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

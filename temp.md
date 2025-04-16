INFO:__main__:Processed response from llama8b API : The encoders in this picture are:

*   **Multi-Head Attention**
*   **Feed Forward**
*   **Add & Norm**

These three components are repeated N times in the encoder.

The **encoder** takes in **INPUT EMBEDDING** and **INPUTS** and outputs a series of vectors that are used as input to the **decoder**.

The **encoder** is composed of a stack of identical layers, each of which comprises two sub-layers:

1.  a **multi-head self-attention** mechanism
2.  a **position-wise fully connected feed-forward network**.

After these two sub-layers, each sub-layer is followed by a **layer normalization** (also known as **ADD & NORM**).

Therefore, there are **three encoders** in the picture:

*   **Multi-Head Attention**
*   **Feed Forward**
*   **Add & Norm**
INFO:__main__:Processed response from llama70b API : The encoders are the components on the left side of the image, within the brown dashed box labeled "ENCODER". 

The encoders are:

*   **MULTI-HEAD ATTENTION**
*   **FEED FORWARD**
*   **ADD & NORM** (there are two of these)
{'llama8b': 'The encoders in this picture are:\n\n*   **Multi-Head Attention**\n*   **Feed Forward**\n*   **Add & Norm**\n\nThese three components are repeated N times in the encoder. \n\nThe **encoder** takes in **INPUT EMBEDDING** and **INPUTS** and outputs a series of vectors that are used as input to the **decoder**. \n\nThe **encoder** is composed of a stack of identical layers, each of which comprises two sub-layers: \n\n1.  a **multi-head self-attention** mechanism \n2.  a **position-wise fully connected feed-forward network**.\n\nAfter these two sub-layers, each sub-layer is followed by a **layer normalization** (also known as **ADD & NORM**). \n\nTherefore, there are **three encoders** in the picture: \n\n*   **Multi-Head Attention**\n*   **Feed Forward**\n*   **Add & Norm**', 'llama70b': 'The encoders are the components on the left side of the image, within the brown dashed box labeled "ENCODER". \n\nThe encoders are:\n\n*   **MULTI-HEAD ATTENTION**\n*   **FEED FORWARD** \n*   **ADD & NORM** (there are two of these)'}

---ABSTRACT---
National flags are the most recognizable symbols of the identity of a country. Similarities between flags may be observed due to cultural, historical, or ethical connections between nations, may be originated from the same group of people, or due to unrelated sharing of common symbols and colors. Although the fact that there are similar flags is indisputable, this has never been quantified. Quantifying flags’ similarities could provide a useful body of knowledge for vexillologists and historians. To this end, this work aims to develop a supporting tool for the scientific study of nations’ history and symbolisms, through the quantification of the varying degrees of similarity between their flags, considering three initially stated hypotheses and using a novel feature inclusion (FI) measure. The proposed FI measure aims to objectively measure the overall similarity between flags based on optical multi-scaled features extracted from flag images. State-of-the-art deep learning models built for other applications tested their capability to be applied for the first time to the problem under study by using transfer learning, towards
calculating the FI measure. More specifically, FI was quantified by six deep learning models: Yolo (V4 and V5), SSD, RetinaNet, Fast R-CNN, FCOS and CornerNet. Flags’ images dataset included flags of 195 nations officially recognized by the United Nations. Experimental results reported maximum feature inclusion between flags of up to 99%. The extracted degrees of similarity were subsequently justified with the help of the Vexillology scientific domain, to support the findings and to raise questions for further investigation. Experimental results reveal that the proposed approach and FI measure are reliable and able to serve as a supporting tool to social sciences for knowledge extraction and quantification.


---FOLDER STRUCTURE---
├── Dataset
    ├── Original Images_1
         000_g0_320.jpg
         000_g0_352.jpg
         000_g0_384.jpg
         ...
    ├── Annotations_1
         000_g0_320.txt
         000_g0_352.txt
         000_g0_384.txt
         ...

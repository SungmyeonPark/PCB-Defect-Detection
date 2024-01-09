# PCB-Defect-Detection
Variational   contrastive   attention   for   weakly-supervised   defect  detection and localization

Abstract.  Detecting small defects  from  images  is  a  fundamental  requirement  in 
manufacturing  applications.  While  traditional  image  processing  techniques  have 
proven effective for addressing certain types of issues, they struggle with challenges 
such as noise, varying lighting conditions, and intricate background textures. Recent 
progressions in the domain of deep learning have yielded substantial enhancements, 
reshaping the landscape of the automated visual inspection industry. However, deep 
learning methods require an extensive amount of precise annotation data, leading to 
costly labelling efforts. To address this challenge, this study introduces a novel deep 
learning model incorporating a variational contrastive attention mechanism designed 
to enhance defect detection and localization performance when provided with only the 
image-level  labels  and  reference  images. The  proposed  deep  learning  model 
concentrates on defect-relevant regions using a learned contrastive spatial attention 
map based on a normal reference image. This method aims to minimize the mutual 
information  between  the  attended  variational  representation  and  the  input  while 
simultaneously  maximizing  the  information  between  the  attended  variational 
representation and class labels. We tested the proposed model on the printed circuit 
board (PCB)  data  to detect  and  localize  small  pollution  defects  in  PCB  images 
without relying on pixel-level annotations. The experimental results illustrate a higher 
level of accuracy in defect detection and the localization of discriminative regions 
compared to competing methods.
Keywords:    Variational    attention,    Contrastive    learning,    Defect    detection, 
Weakly-supervised learning

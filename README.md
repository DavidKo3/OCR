# OCR
## Recognition - SOTA Performance (only unconstrained lexicon-free)
* TTM : Total-Text (multi-oriented) 
* TTC : Total-Text (curved)
* 학습셋
  * SK : Synth90K
  * ST : SynthText
  
| Paper | SVT | IIIT5k | IC03 | IC13 | SVTP | CUTE80 | IC15 | TTM | TTC | 비고 | 학습셋 | 
| --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |--- |--- |
| SOTA|  **89.5** | **94.0** | **94.7** | **94.4**| **80.6** | **88.5** | **77.1** | **76.3** | **66.7** |
| [1] | 80.8 |  78.2 | 89.4 |  86.7 | 66.8 | 54.9 | | | | base:CRNN | SK| 
| [2] | 88.6 | **94.0** | 93.6 | 93.2 | **80.6** | **88.5** | **77.1** | **76.3** | **66.7** | Rectification | SK+ST |
| [3] | 87.1 | 89.4 | **94.7** | 94.0 | 73.9 | 62.5 | | | | GAN |  
| [4] | **89.5** | 93.4 | 94.5 | 91.8 | 78.5 | 79.5 | 76.1 | | | Rectification |
| [5] | 82.8 | 87.0 | 91.5 |  | 73.0 | 76.8 | 68.2 | | | AON |
| [6] | 87.5| 88.3 | 94.6 | **94.4**  | | | 73.9 |
| [7] |  90.2 | 93.3 | | 91.3 | 79.6 |  83.3  | 76.9 | | | Rectification | SK+ST |

* [1] An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition
* [2] Recurrent Calibration Network for Irregular Text Recognition
* [3] Synthetically Supervised Feature Learning for Scene Text Recognition : [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/html/Yang_Liu_Synthetically_Supervised_Feature_ECCV_2018_paper.html)[[review]](https://github.com/chullhwan-song/Reading-Paper/issues/60)
* [4] ASTER: An Attentional Scene Text Recognizer with Flexible Rectification
* [5] Arbitrarily-oriented text recognition
* [6] Edit Probability for Scene Text Recognition
* [7] ESIR: End-to-end Scene Text Recognition via Iterative Rectification

## Detection
* R : Recall
* P : Precision
* F : F-measure
* MS : MSRA-TD50
* TT : Total-Text

| Paper | IC13-R |IC13-P |IC13-F| IC15-R |IC15-P |IC15-F| MS-R |MS-P |MS-F|TT-R |TT-P |TT-F|
| --- | --- |--- | --- |--- |--- | --- |--- |--- | --- | --- |--- | --- | 
| SOTA| **88.6** |**93.34**   | **90.34** | **82.0** |**86.1** | **83.7**  | **83.0**|**87.28**| **80.21**| **54.41** | **59.89** |  **57.02** |
| [1] | 87.53    | **93.34**  | **90.34** | 78.33    | 83.27   |  80.78    | 67.43   |**87.28** |  76.08 |
| [2] | 85.94    | 93.18      | 89.41     | 79.2     | **86.1** | 82.5     |75.26    |  85.88  | **80.21** | 
| [3] | **88.6** | 87.5       |  88.1     | **82.0** | 85.5    |  **83.7** | **83.0**| 73.2    | 77.8 | **54.41** | **59.89** |  **57.02** |


* [1] East: An efficient and accurate scene text detector
* [2] Detecting Text in the Wild with Deep Character Embedding Network
* [3] Pixellink: Detecting scene text via instance segmentation

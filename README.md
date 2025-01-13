# Image-Content-Analysis-Clothing-Recommendations
The goal of this work is to provide decison-support to the customers in their shopping selections.
This idea comes up with the images analysis of a customer's shopping selections and provide top three recommendations out of his/her selections.

This work conducted in following steps:

1) Performed training of **VGG16 Neural Network** for three main attributes of a cloth i.e. **Fabric, Pattern, and Style**
2) Three models developed, each trainined on separate dataset. Fabric dataset contained 6 classes, pattern dataset contained 47 classes, and style dataset contained 14 classes.
3) For a given clothing item, the outcomes of second-last layer of three models were concatenated to generate a comprehensive vector representation.
4) The cosine similaity-based strategy among vector representation of clothing items was employed to provide an ordered list of recommendations.

This work was employed in a paper where this approch comparatively analysed with some other SOTA approaches. The repective paper is here:

**Aayesha, A.**, Afzaal, M. and Neidhardt, J., 2024. Social Circle-Enhanced Fashion Recommendations System.

   

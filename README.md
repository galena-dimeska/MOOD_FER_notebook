# Contents

This repository contains the Jupyter Notebook (.ipynb) for the "Deep Learning Approach for Facial Expression Recognition in Images with OCOsense Glasses-Worn Faces" project as well as the paper (.pdf) which provides a detailed explanation of the project's goals, experiments and results.

![alien_1](https://github.com/galena-dimeska/FER-with-Deep-and-Transfer-Learning/assets/125221651/54b03fd0-79b0-411f-9b4c-50d3056445a6)


# Abstract

Deep learning is a very important type of field within the machine learning sphere that is extremely beneficial and instrumental for data science, especially where collecting, analyzing and interpreting large 
amounts of data is concerned. In this study, ten different image classification models were defined and evaluated using deep learning methods, with the goal of finding the ones that would be best suited for facial expression recognition of a person wearing Emteq labs’ OCOsense glasses. The initial data was extracted from the frames of the MOOD data collection videos of 20 subjects in the form of images. The data was then manually categorized into the desired classes (eyebrow_raise, frown, neutral, smile), and undersampling was performed on the majority class, neutral. The models were then defined, trained for the same number of epochs and evaluated in the same way. The results confirmed that simple models with few convolutional layers would perform worse in general, however a notable trend among the complex models where transfer learning was utilized showed that the results favored those models whose convolutional bases were fully trainable, as opposed to the ones where fine-tuning and freezing the lower layers was the technique used. The best model in terms of performance on the test set achieved an accuracy of 85.44%.

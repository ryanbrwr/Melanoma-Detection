# Melanoma Detection
### Summary

Sebastian Thrun, Co-Founder of Udacity, created an algorithm that can detect Melanoma as well as many other skin diseases just from a photo. Himself as well as two graduate students at the University of Stanford created the model on 130,000 images of skin lesions from the ISIC database.


### Running on your computer

Here are the following steps in order to run the code locally or in the cloud:
1. Clone the repo: `git clone https://github.com/RyanBrew/Melanoma-Detection`
2. Run the notebook!

If you encounter any errors during installation, don't hesitate and open an [issue](https://github.com/RyanBrew/Melanoma-Detection/issues).

### Data 

The data has been made available by Udacity through the ISIC database.

* [training](https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/train.zip)
* [validation](https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/valid.zip)
* [testing](https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/test.zip)

### Future

* Train with crops of 1024x1024, not windows of 512x512.
* Use data from multiple sources instead of only ISIC
* Set up a cloud instance to train a much deeper model than the current AlexNet solution.
* Train with more data (in the cloud?)

### Limitations

This project has been developed in a few days by 1 person and, therefore, many limitations have appeared.
They will be listed below in order to give a sense about what this project is and what it's not.

* **Computing power/memory**: Development of the project has taken part in a computer with the following specs: Intel i7-6700k, 8gb RAM, NVIDIA GTX-1080Ti 8gb and 256gb of storage. The capacity for data exploration, processing, training and evaluating the models is limited.
* **GPU/TPUs for training**: The models were trained and evaluated on a single GPU. No cloud servers were used. 
* **Time**: A few days of development during spare time.
* **Domain expertise**: No experts in the field. The author knows the basics of Deep Learnning.
* **Data**: The ISIC truncated dataset made available by Udacity. 

Due to these limitations and/or constraints, the precission/accuracy the methods here developed can achieve is limited when compared against SOTA algorithms.


### Contribute
Hey there! New ideas are welcome: open/close issues, fork the repo and share your code with a Pull Request.
Clone this project to your computer:
 
`git clone https://github.com/RyanBrew/Melanoma-Detection`
 
By participating in this project, you agree to abide by the thoughtbot [code of conduct](https://thoughtbot.com/open-source-code-of-conduct)
 
### Meta
 
* **Author's GitHub Profile**: [Ryan Brewer](https://github.com/RyanBrew/)
* **Twitter**: [@RyanPrograms](https://twitter.com/ryanprograms)
* **Email**: ryanbrew13@gmail.com

* **ReadMe Template**: [@EricAlcaide](https://github.com/EricAlcaide/MiniFold)

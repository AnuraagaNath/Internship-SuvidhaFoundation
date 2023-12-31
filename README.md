
# SimCLS: Text Summarization 

This project are done under ML Internship under Suvidha Foundation (www.suvidhafoundationedutech.org) from 25th of August 2023. 

The project mainly focused on the Research paper "SimCLS: A Simple Framework for Contrastive Learning of Abstractive Summarization" by Yixin Liu and Pengfei Liu from Carnegie Mellon University.

This paper suggests that using two stage model for abstractive summarization.
Here what I did while following the paper using Pytorch in Google Colab platform. I will work on this later on time. So the files will get updated over time upon progress.

Firstly, the data is cleaned with proper steps like using contractions, removing stopwards, regular expressions, lowercasing the text. 

Secondly, a Seq2Seq model (Bart-large from hugging face, any other similar model can be used but it worked prefect for me) and train the cleaned data with it with using custom values of epochs, batch size, evaluation process, steps.

Thirdly, using a evaluation metrics (Rouge 1/2/L) to check the model output with reference one. As I have taken less data to train the model for my less computational power availability, I got a lower rouge score in this project.

Get the data from this Link: https://drive.google.com/drive/folders/1feZb9bKGB6qc-x0XZd_1QElaoE8QBRkX?usp=sharing 
Edit the directory according to your needs.


## Environment Variables

As per September 20, 2023 the versions of the packages are as follows.

`accelerate version: 0.24.0.dev0`

`transformers version: 4.33.2`

`datasets version: 2.14.5`

`Python version: 3.10.12`

`PyTorch version: 2.0.1+cu118`






## Documentation

[SimCLS: Documentation](https://drive.google.com/file/d/1YYN2rRIyEcISDOWQAwBQ8bSKYtHZIuel/view?usp=sharing)


## Authors

- [@AnuraagaNath](https://www.github.com/AnuraagaNath)


## Feedback

If you have any feedback, please reach out to me at anuraagadec10@gmail.com


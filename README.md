# music-genre-classification
Music genre classification from audio spectrograms using deep learning
A convolutional neural network is trained with 7000 sample audios of 10 different music genres. 
  
**GENRES**: blues - classical - country - disco - hiphop - jazz - metal - pop - reggae - rock  
  
**DATA**: [GTZAN Genre Collection](http://marsyasweb.appspot.com/download/data_sets)  
             
## Usage  
$**python3**  get_genre.py  input-audio-path  
  
### Example  
$**cd**  src  
$**python3**  get_genre.py  ../test.mp3  
**--> disco**: 62.50%  
**--> rock**:  35.42%  
**--> reggae**: 2.08	%  
   
Test audio (test.mp3) is a disco song, **Every 1's A Winner** by **Hot Chocolate**. (*https://open.spotify.com/track/5MXXbGYNmRHR7ULMvZYo5R?si=yk6GzvJiS--7hZuGd8awog*)   

#Install the required Python libraries.
Create a virtual environment and activate it.

Install the project dependencies.
Train the model.
Evaluate the model.
Make predictions.
Here are the detailed instructions for each step:

To clone the GitHub repository, run the following command in your terminal:
git clone https://github.com/cetinsamet/music-genre-classification.git

To install the required Python libraries, run the following command:
pip install -r requirements.txt

To create a virtual environment and activate it, run the following commands:
python3 -m venv venv
source venv/bin/activate

To install the project dependencies, run the following command:
pip install -e .

To train the model, run the following command:
python train.py

To evaluate the model, run the following command:
python evaluate.py

To make predictions, run the following command:
python predict.py
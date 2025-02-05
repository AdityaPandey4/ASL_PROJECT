This is my first project in AI/Ml using object detection 

# Abstract
According to the World Health Organisation, 300 million people are deaf and 1 million
people are dumb currently. It is not possible for them to communicate with others
through spoken languages. Therefore, they resort to sign languages where the
communication happens through different hand signs, each having their own meaning.
But the problem here is that the remaining population who never had to learn these sign
languages find it difficult to understand these signs and interpret its meaning.
As solution, this project aims to develop an American Sign Language (ASL) processing
system to facilitate communication between deaf individuals who use American Sign
Language and the general population

# Problem Statement 
The problem at hand is the communication gap between ASL users and non-ASL users.
The lack of widespread ASL fluency inhibits effective communication and inclusivity,
hindering the full participation of deaf individuals in various domains of life.
Through this project we are trying to provide a system that can not only help the 
general public but especially help the doctors to understand ASL ( American Sign 
Language ) and provide better diagnostics.

# PROPOSED DESIGN:

The design for the ASL processing project consists of several key components that work
together to accurately recognize and interpret ASL gestures in real-time. The proposed
design encompasses data collection, signs recognition model development, and system
integration.
## Data Collection:

To build a robust ASL processing system, a comprehensive dataset of ASL signs
representing a wide range of vocabulary and expressions was collected. This dataset
served as the training data for the gesture recognition model. Various cameras or depth
sensors can be used to record the ASL signs from different angles and perspectives.

## Sign Recognition Model Development:

The core of the ASL processing system lies in developing an accurate and efficient
signs recognition model. This model will leverage machine learning algorithms, such
as convolutional neural networks (CNNs), to classify and interpret ASL signs. The
collected dataset was used to train the model, with appropriate data preprocessing
techniques applied to enhance the model's performance.

The CNN model used here is SSD Mobilenet V2. It is a one-stage object detection
model which has gained popularity for its lean network and novel depth wise separable
convolutions. It is a model commonly deployed on low compute devices such as mobile
(hence the name Mobilenet) with high accuracy performance. 

# Results
- EVAL MATRICES AT 2000 STEPS
  
![tb2](https://github.com/user-attachments/assets/3ec7719c-0e97-46ff-bb81-924e6ad9aca0)

LOSS

![tensorboard4](https://github.com/user-attachments/assets/54cdc690-b10e-4ba4-a2fe-4a6a1bbdfaff)

Final Result
![trimed eval](https://github.com/user-attachments/assets/f9b01b69-93c3-4561-9ea0-7594a709179b)

![tbeval11](https://github.com/user-attachments/assets/177ab17b-98b0-4751-87d5-3828391cf221)

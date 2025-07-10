# End-to-end-Medical-Chatbot-using-Llama2

#Steps to run the project

# TO create Virtual Environment we use the following command:

conda create -n mchatbot python=3.10 -y

# to activate the environment, use the following command:

conda activate mchatbot

# to install the requirement, create a requirements.txt file and add all tha packages name here and install all the packages with the help of following commmand:

pip install -r requirements.txt

# to install again or to force reinstall in requirements.txt we can use the following command:

pip install -r requirements.txt --force-reinstall

# now we get the api key from pinecone website and also there we create index and select dimenstion, that dimension should be equal to our embedding model (we use embedding model from hugging face hub, there model dimensions are given in their descriptions. )

# here we are using the following embedding model
sentence-transformers/all-MiniLM-L6-v2   --> has dimension of 384


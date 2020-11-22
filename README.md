# Question-Answering-Model-on-context

Steps To Run It:

1)Create a new envrionment and Install All The required dependencies ( install flask_ngrok if you want to host it)\n
2)Then Run the cell for Downloading dataset which is available at "https://rajpurkar.github.io/SQuAD-explorer/dataset/" (Only For training)
3)Run all the cells of all layers
4)Then if you want to train the model
  i) if you want to continue the tranining then run the cp cell to copy the model to current session
  ii) If you don't want to continue then skip this cell and continue on the next cell 
  (It will take 3-4 hours to run one epoch)
5) For running testing A flask website will be created and with the help of ngrok you will be able to test it online (This is little flawed right now)
6) Otherwise, you can direcly test it by creating a new model and loading your trained model and then passing the query and context to it.



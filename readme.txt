this project is divided as 3 parts.

1. Image preProccessing
2. Deep-Learnig
3. Server

each parts should includes 2 more python files.

1.Image preProccessing
  -preProccessing.py
    {
      pre-proccesing Image data transmitted by client as known as application.
      it has 2 function for pre-proccessin, 'find.explore_img' and 'trim. for'. for convenience, im calling fucntions as a,b      
      compare prediction-rate about a,b. return a higher value that is maked by different pre-proccessing image.
      }
      
  -trim.py
    {
      it is included preProccessing. 
    }
    
    whole this part isn't mine. but also connecting functions, and comparing argorithm 
  
 2.Deep-Learnig
  -image_gen.py
    {
      adjusting image argument to make 20 images that isn't dependece for model overfitting through 1 image
    }
    
  -make_model_json.py
    {
      train model, and save model.json, model_weight.json 
    }
    
  -deeplearnig.py
    {
      define the function as prediction. function make a label data dependent on Deep-Learning model prediction.
    }

3.Server
  -server.py
    {
      connect client application. take image files, and save for reinforce training that is not yet
      transmit label data
    }
  

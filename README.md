# Algorithm_04

### MODEL1
1-1. MODEL1

      if model_number == 1:
        model = keras.models.Sequential([
                    keras.layers.Conv2D(32, (3,3), activation = 'relu', input_shape = (28, 28,1)),  # layer 1 
                    keras.layers.MaxPool2D((2,2)),                                                  # layer 2 
                    keras.layers.Flatten(),
                    keras.layers.Dense(10, activation = 'softmax')])                                # layer 3
             
            
1-2. Training with training loss and test accuracy
![image](https://user-images.githubusercontent.com/76681519/173243493-43b79d59-bd2b-4766-8cf0-97679de2dfc9.png)


1-3. Images and corresponding probability that predicted Right

![image](https://user-images.githubusercontent.com/76681519/173243747-1b97ce2e-ed25-4dc7-8cee-75da72ca4eed.png)
![image](https://user-images.githubusercontent.com/76681519/173243544-aaef4d95-5740-429b-9896-ffeee63b628e.png)


1-4. Images and corresponding probability that predicted Wrong
![image](https://user-images.githubusercontent.com/76681519/173243573-77c9b9a1-a70f-4739-a885-3d961b997c63.png)


### MODEL2
2-1. MODEL2

    if model_number == 2:
        model = keras.models.Sequential([
                    keras.layers.Conv2D(32, (3,3), activation = 'relu', input_shape=(28,28,1)),     # layer 1 
                    keras.layers.MaxPool2D((2,2)),                                                  # layer 2
                    keras.layers.Conv2D(64, (3,3), activation = 'relu'),                            # layer 3 
                    keras.layers.MaxPool2D((2,2)),                                                  # layer 4
                    keras.layers.Flatten(),
                    keras.layers.Dense(10, activation = 'softmax')])                                # layer 5
                    
                    
2-2. Training with training loss and test accuracy
![image](https://user-images.githubusercontent.com/76681519/173243596-6b4ffa92-8002-4d4e-b60d-1734c59b9591.png)


2-3. Images and corresponding probability that predicted Right

![image](https://user-images.githubusercontent.com/76681519/173243756-5cfc80d9-641f-4e3b-ae30-7031f6d91b2b.png)
![image](https://user-images.githubusercontent.com/76681519/173243622-40050994-00b6-4b4d-86e9-29f202a91b6c.png)


2-4. Images and corresponding probability that predicted Wrong
![image](https://user-images.githubusercontent.com/76681519/173243631-ea30fb92-9937-49f8-a45d-c22e885d8970.png)



### MODEL3
3-1. MODEL3
                     
    if model_number == 3: 
        model = keras.models.Sequential([
                    keras.layers.Conv2D(32, (3,3), activation = 'relu', input_shape = (28, 28,1)),  # layer 1
                    keras.layers.MaxPool2D((2,2)),                                                  # layer 2
                    keras.layers.Conv2D(64, (3,3), activation = 'relu'),                            # layer 3
                    keras.layers.Conv2D(64, (3,3), activation = 'relu'),                            # layer 4
                    keras.layers.MaxPool2D((2,2)),                                                  # layer 5
                    keras.layers.Conv2D(128, (3,3), activation = 'relu'),                           # layer 6
                    keras.layers.Flatten(),
                    keras.layers.Dense(10, activation = 'softmax')])                                # layer 7
    
    
3-2. Training with training loss and test accuracy
![image](https://user-images.githubusercontent.com/76681519/173243658-64cb446a-ca72-4ed4-8fe1-3f8875d977cc.png)


3-3. Images and corresponding probability that predicted Right

![image](https://user-images.githubusercontent.com/76681519/173243767-c51fa145-78c0-4c57-8f17-af61bcc9806b.png)
![image](https://user-images.githubusercontent.com/76681519/173243666-b08c7455-1963-40f1-ab8d-a21760f223e3.png)


3-4. Images and corresponding probability that predicted Wrong
![image](https://user-images.githubusercontent.com/76681519/173243678-9416f531-e5c1-4f61-b739-c0b9c572bace.png)


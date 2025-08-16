# interspeech-gradual-lombard
This repository contains the sound files used on the listening test of the Interspeech 2025 paper "Gradual modeling of the Lombard effect by modifying speaker embeddings from a Text-To-Speech model". The main idea of our work is to modify the speaker embeddings of a TTS model to generate the main contribution of a "Lombard transformation" while compensating the "easy parts", namely signal level and duration, with easier methods.  
 
## Listening Test
 
We evaluated four sound groups under varying background noise:
 
- **LG-II**: Ideal interpolation with correct Lombard embeddings  
- **ITU-FT**: Our zero-shot Lombard conversion  
- **ITU-LO**: Current ITU-T P.1150 recommendation  
- **RS**: Random speakers (identity anchor)  
 
Background noise: loud restaurant.

Some examples of each group can be seen below: 

### LG-II 

Generations done with embeddings from real Lombard speech. 

https://github.com/user-attachments/assets/dff999cc-5cb9-496c-b428-d9e2e8c4db47

https://github.com/user-attachments/assets/613e49ad-ac68-42e2-a590-0f991fd41032

### ITU-FT 

Zero-shot Lombard speech generation (our main contribution). 

https://github.com/user-attachments/assets/2a966a78-ffc9-44cb-807b-a31c16b7c98a

https://github.com/user-attachments/assets/0f028379-7142-4598-9854-63b637a628e4


### ITU-LO 

Current ITU-T P.1150 standard, only level is changed. 

https://github.com/user-attachments/assets/3fdae96b-59d2-43ef-92f7-796ff5a41085


https://github.com/user-attachments/assets/d6186f17-0f64-43f7-ad94-c9edae4ef18f



### RS

Generation with random speaker embeddings.

https://github.com/user-attachments/assets/2070d9a1-a990-41c9-bc40-3766eeb7a7a2



https://github.com/user-attachments/assets/0866034b-d863-4b7e-8281-8920ad54e45f



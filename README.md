# Synonyms-Antonyms-Python
Using python how to get synonyms of a word and how to deal with antonyms.  

Note - This is one of the early python codes I wrote, can be improved a lot but this also works and suffices the purpose, can be modified according to your requirement.

For Synonyms  
Python package - nltk (loaded with required corpus), textblob  
.py file - Synonyms.py  
Code logic -    
            Identify the pos tag of each word in sentence  
            Pick the required indices from sentence which satisfies your POS condition  
            Do find 3 synonnyms for each identified required POS tag word  
            Then replace the sentences with those synonyms found for each word keeping rest sentence same  
              
                
For Antonyms  
Python package - nltk  
.py file - Antonyms.py  
Code logic -  
            Check if the words in sentences have "not"  
            If "not" is found replace not and the immediate next word with antonym of the word next to "not"  
            If "not" is not found then keep the words as it  
            Now join all the words after replacement and thats the final sentence  
            

         
          

# how-do-we-deploy-meta-llama-Llama-3.2-1B-on-huggingface-
hi, so i was doing  a project, and i had wasted a lot of time in trying to debug my code  to make a gradio app at hugging face, so i want people who might struggle in this not to waste any time here
so for starters, we first have to search that model, and all we have to do is search Llama 3.2:1 on google and then we will land on the huggingface model(this is the link if required: https://huggingface.co/meta-llama/Llama-3.2-1B)
after going there we have to scroll down and fill the form which will confirm our identity, and after filling that form , we will get the access of the model and it will be shown like this ![image](https://github.com/user-attachments/assets/387b33bb-c52b-4be5-b186-020c2d102f88)
after getting the access we need to make a space, and make two files are necessary there, requirement.txt and app.py
Before working on the files, we will have to make sure that we make a token, and keep it as a secret in our space
![image](https://github.com/user-attachments/assets/506ddf74-9e08-45a0-b2e6-4a26931413a8)


after that is done, just copy and paste the code from this rep, and this should be enough, please make sure to name your token HF_Token if you directly wanna use this
Just update requirement.txt, and app.py and you are done
thanks for reading so far
it would be faster if you have a Gpu in spaces, but works fine with cpu 16gb as well, but you will have to wait for atmost a min for response 
![image](https://github.com/user-attachments/assets/70047827-e51f-4619-81a3-588d3f2a3a6a)


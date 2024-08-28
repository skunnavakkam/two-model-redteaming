I remember playing a game. We give the model a secret in its prompt somehow. The attacker then has to find out the secret. We do something similar here, except you have one model "protecting" the other model, by prompt engineering for it. 

I choose gpt-4o as the red-teamer and prompter, and choose gpt-3.5-turbo as the guard. 4o-mini just doesn't let go!

To run:
```
pip install openai
python main.py
```
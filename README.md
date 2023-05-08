# David
David is a programming legend. 

In this simple bash script, I made a tribute to him while playing with colors using ASCII escape sequences.

## Making it available as command everywhere

<p> You can run this script with the following command, provided it's in the same directory where you execute it: </p>
> ./david

But this doesn't do David justice. You want to make this command available everywhere.
- Add your /home/user/bin to the PATH variable (or whichever directory you prefer):
> ```export PATH=$PATH:/home/user/bin```
- Make sure david is in that directory.
- Run the following command:
> ```source ~/.bashrc```
- You're good to go! Enjoy!

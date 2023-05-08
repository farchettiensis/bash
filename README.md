# David
<p> David is a programming legend. 

In this simple bash script, I made a tribute to him while playing with colors using ASCII escape sequences.</p>

## Making it available as command everywhere

<p> You can run this script with the following command, provided it's in the same directory where you execute it: </p>
> ```./david```

But this doesn't do David justice. You want to make this command available everywhere.
- Add your /home/user/bin to the PATH variable (or whichever directory you prefer) and move the script to that directory:

> ```export PATH=$PATH:/home/user/bin```


- Run the following command:

> ```source ~/.bashrc```

You're good to go! Just run 'david' on the terminal and enjoy!

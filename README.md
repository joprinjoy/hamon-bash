# hamon_bash
##Bash.

__Bash-__ was not a strange name for me. I have already heard it many times. Same for shell scripting. Heard many times,know it exist but don't know what ,how, and why.

 I have already had my hands on Linux and terminal from college, so that mkdir, ls,cd, cat,grep,cp,mv commands were familiar for me. But other than the basic usage I was not matured enough to play with these commands. After the first session on Unix from bala,I regained my confidence to play with terminal,and many more commands and multiple usages learned.

My first problem was the __./__ usage  while copying or moving something. Even I was told it represents the current directory I didn't understand it . For the records, now I started using it on daily basis.

I was not fully confident about command line operations  until I started using git for every code I write.

I try to catch up from the sessions morover online refference. So that ,it may be reflecting in my codes that usages of ways or methods that discussed in the sessions. For example,I used __test -lt , -gt __ in my ARI script where almost others directly used __< >__ . But I try do try them to make sure it is working for me to..

Moreover learning something new, I felt  reading the unix as revision and detailing to  the contents discussed in the sessions. Different usages and ways of using commands making it interesting..

Binding the commands to create new commands for different purposes was bit tricky for me, I didn't make it most the time. But I was able to fix later.So that I can write them I believe.

I thought creating ARI shell script was not a big challenging task .

I started with another question that,how to read a file?  Without any second thought process I just typed the same question in chatgpt.  
First thing learned was __filename=$1__
After understanding what it does, my whole questions were cleared for some time.
 Taking the word count ,charecter count was easy because we already done it in the past.. But taking count of the sentence was not easy  for the records I didn't used any side of the brain to figure out the logic. Chat gpt was there to provide the line of code.

But I understood the logic of taking a sentence count and that helped writing code myself for the same purpose in another language.

One problem faced at this point was printing the result alone. Everytime I use to print the result,it always printing the filename alongside. So tried __<__ redirection as a ' try' and it worked.The joy was hell..


The sad part of writing ARI code was when I realised that shell don't play with with arithmetic operations and floating numbers directly. So again I have to do research to solve it and I came up with 'bc-basic calculator' with the help of chatgpt again.

Floating points become the pain again while comparing the result with other values. So again chatgpt showed her helping hands to learn about scale and then rounding up the values..

Wikipedia had given litle more clarity on grading and ARI values so the same used in the script..


After geting the correct output I decided to take the filename from the user as an input and changed it quickly.. unfortunately code still working .

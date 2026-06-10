## Week of 31st May 2026

Made a basic webcam program in Python with my teacher. After the session I went through the code line by on my own. With the help of Claude and some experimentatial I atchully understood what every part does.

I understood that first the code gets the camera that you are going to use, if your camera is not working it will print that you can not open camera, while it is able to recieve your camera it will get your frame, if not able to get the frame it will print that it cant your frame then it will start the camera and when you press Q it will close all the windows.

Need to figure out: waitkey(1)

## Week of 10th June 2026

Made the following programs in python this week:

### Check if a number is positive, negative or zero

### Check if any number is divisble by 5 and what is the quotient

### Compare two numbers and show which one is larger

### Check if an alphabet is a vowel or not

we would type an alphabet and check if it is a vowel then return the value

### Check how many vowels are there in a word and give the number as output


#### What was confusing
- My loop variable was named `vowel` — same as my counter. So when the loop ran, it kept overwriting the count with the loop value instead of adding to it. I thought `len` was the problem but it was actually the variable name clash.
- I was also checking `word == 'a'` instead of each character, so it was comparing the whole word to a single letter, which never worked.

def vowel(word):
  vowel=0
  for vowel in range(len(word)):
   if word=='a' or word=='i' or word=='o' or word=='e' or word=='u':
    vowel=vowel+1
  return vowel

#### What's next
- Try counting consonants the same way
- Make it work for a whole sentence, not just one word
- Maybe count how many times each vowel shows up separately




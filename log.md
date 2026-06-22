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


## Week of 21st June 2026

My project that i started 3 weeks ago is to make a lego ai inventry that scans and saves all lego pieces and then tells me what i can make from it.

### What I learnt

So far I have made the following code files: 

opening_the_camera.py :  i learnt about cv2 that is computer vision, waitkey that tells us how long to wait for our frame, ord that converts what i wrote to ascii, and i learnt videocapture that tells the computer which camera to use

create_a_folder.py: i learnt makedirs that creates a folder if it does not exist

saving_an_image.py: i learnt about datetime gives the computer the time with %y%M%D%H%M%S%F that is year, month, day, minute, second, and microsecond

resizing_an_image.py: i learnt about resize that resizes an image however you want, and image.shape that gets the shape of the image

### What was confusing

opening_the_camera.py: i got confused in what waitkey does.
Solution: it waits for the amount of micro seconds you give.

create_a_folder: i got confused in what makedirs  does
solution: it creates a folder if it does not exist

saving_an_image: i got confused in why we need frame 
solution: we need frame because it gets the space the camera needs

resizing_an_image: i got confused in how imwrite resizes an image
solution: it gives the name to the resized image.

### What's next

make a code to identify a lego brick with color and name
# magic-word
# Just a beginner python program for displaying famous 'you didn't say the magic word' output

print("Jurassic Park System Security Interface")
print ("Version 4.0.5, Alpha E")
print("Ready...")
print ("> access security ")
print("access : PERMISSION DENIED ")
print ("> access security grid")
print("access : PERMISSION DENIED ")
print ("> access main security grid")
print("access : PERMISSION DENIED...and... ")
print("YOU DIDN'T SAY THE MAGIC WORD\n" * 20)

from IPython.display import Image, display

url = "/content/you-didnt-say-the-magic-word-ah-ah.gif"

while True :
  display(Image(data=url, width=200, height=200))
  break

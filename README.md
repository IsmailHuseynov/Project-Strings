# Project-Strings
an_letters='aefhilmnorsxAEFHILMNORSX'
word='MIT'
times=10
i=0
while i<len(word):
    char=word[i]
    if char in an_letters:
        print("Give me an "+char+"! "+char)
    else:
        print("Give me a "+char+"! "+char)
    i+=1
print("What does that spell ?")
for i in range(times):
    print(word,"!!!")

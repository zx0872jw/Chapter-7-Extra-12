# Chapter-7-Extra-12
# Write the print statement... print(' '.join(pig_latin)) on line 10
string = input("Enter a sentence: ")
words = string.strip().split(' ')
pig_latin = []
 
for word in words:
    pig_latin.append(word[1:] + word[0] + 'AY')
 

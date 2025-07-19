# py-26
counting specail charecters in input
def special_char(s):
    count=0
    for i in s:
        if i.isalnum():
            count==0
        else:
            count+=1
    return count
print(special_char("hi#&$$99"))

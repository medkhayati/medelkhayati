class lover :
    def __init__(self, beauty, carness, is_loving, missing ,thinking):
        self.beauty = beauty
        self.carness = carness
        self.is_loving = is_loving
        self.missing = missing
        self.thinking = thinking
khadija = lover("you are wonderfull Queen " , "he is always caring about you " , True , "he missed you so much" , "he would never think about other girl")
#print(khadija.is_loving)
q1 = "am i beautifull"
q2  = "does he care about me"
q3 = "does he love me"
q4 = "does he miss me"
q5 = "does he think about another girl"
word = input("enter a question: ")
if q1 ==  word:
    print(khadija.beauty)
elif q2 ==  word:
    print(khadija.carness)
elif q3 ==  word:
    print(khadija.is_loving , "akter ma katkhayli Miss Queen")
elif q4 ==  word:
    print(khadija.missing)
else :
    print(khadija.thinking)


# Crazy-quizz
score=0
print("welcome to crazy quizz 😃!..")
print("here we are going to learn crazy facts together")
input("do you wnat to continue🧐?.. ")
easy_or_hard= input("do you want to start with easy or hard ? 🫣")
if easy_or_hard == "easy" or "Easy":
    knowing_the_capital_of_italy_one=input("do you know tge capital of italy ? yes or no..👀 ")
    if knowing_the_capital_of_italy_one=="yes" or "Yes" :
        capital_of_italy=input("what is the capital of italy 🫣??: ")
        if capital_of_italy=="Rome"or "rome":
             score = score + 1
             print(f"good job 😄!.. your score now is : {score}")
        else :
            print(f"wrong answer 😕.. your score now is {score+0}😭")
    elif knowing_the_capital_of_italy_one=="no" or "No":
        print("the capital of italy is Rome")
        print("now you know it🎉")
        print("so let's test you 😃!..")
        knowing_the_capital_of_italy_two=input("what is the capital of italy 🫣: ")
        if knowing_the_capital_of_italy_two== "italy" or "Italy" :
            score +=score
        else :
            score -= score
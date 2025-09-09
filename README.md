# Crazy-quizz
print (" hello friend , make sure to make an acc ")
username = input (" what's ur username 🤔 : ")
password = input (" what's ur password 🔑 😶‍🌫️ : ")
#log in 
username_1 = input ("enter your username here : ")
password_1 = input ("enter your password here : ")
if password == password_1 and username == username_1 :
    print ("good welcome to ur acc " + username)
    

score=0
print("welcome to crazy quizz 😃!.." + username)
print("here we are going to learn crazy facts together")
input("do you want to continue🧐?.. ")
easy_or_hard= input("do you want to start with easy or hard ? 🫣")
if easy_or_hard == "easy" or easy_or_hard == "Easy":
    knowing_the_capital_of_italy_one=input("do you know the capital of italy ? yes or no..👀 ")
    if knowing_the_capital_of_italy_one=="yes" or knowing_the_capital_of_italy_one == "Yes" :
        capital_of_italy=input("what is the capital of italy 🫣??: ")
        if capital_of_italy=="Rome" or capital_of_italy == "rome":
             score += 1
             print(f"good job 😄!.. your score now is : {score}/10 ")
        else :
            print(f"wrong answer 😕.. your score now is :{score}/10 😭")
    elif knowing_the_capital_of_italy_one=="no" or knowing_the_capital_of_italy_one == "No":
        print("the capital of italy is Rome")
        print("now you know it🎉")
        print("so let's test you 😃!..")
        knowing_the_capital_of_italy_two=input("what is the capital of italy 🫣: ")
        if knowing_the_capital_of_italy_two== "rome" or knowing_the_capital_of_italy_two == "Rome" :
            score += 1
            print(f"congratulation 🥳🎉 you learned something new.. your score now is : {score}/10 ")
        else :
            print(f"revise what we teched you 😾 !! your score now is : {score}/10 😕")
else : 
    print ("you didn't choose a valid option🙄🫨 !!")
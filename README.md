# stone-paper-scissor
move = input("Enter your move :")
import random
rand_num = random.randint(0,2)
if rand_num== 0:
    print("stone")
elif rand_num== 1:
    print("paper")
elif rand_num== 2:
    print("scissor")

if move==rand_num:
    print("tie")
elif move=="scissor" and rand_num==1:   
    print("u win")
elif move=="paper" and rand_num==2:   
    print("u lose")    
elif move=="stone" and rand_num==2:   
    print("u win")   
elif move=="scissor" and rand_num==0:   
    print("u lose")
elif move=="paper" and rand_num==0:   
    print("u win") 
elif move=="stone" and rand_num==1:   
    print("u lose")    

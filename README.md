import random

def game():
    
    name=str(input("Enter your name :"))
    print("Welcome ",name)
    print("Welcome to jumble game :")
    print("Here are some rules of game")
    print("""1 :There will be total 10 question
    2 :For each right answer you get 10 point
    3 :For each wrong answer your point will be min. by 2 point
        4 :When you enter your ans. enter only first word captial |""")
    newlist=[]
    point=0
    mylist=["Elephant","Python", "Laptop", "Planet", "School", "College", "Friends", "Holiday", "Library", "Teacher", "Student", "Science", "Kitchen", "Garden", "Travel", "Mobile", "Bottle", "Charger", "Battery", "Window", "Curtain", "Blanket", "Pillow", "Station", "Printer", "Coffee", "Cinema", "Temple", "Castle", "Bridge", "Riverbank", "Diamond", "Factory", "Village", "Stadium", "Airport", "Theater", "Camera", "Speaker", "Bicycle", "Rocket", "Forest", "Desert", "Galaxy", "Sunrise", "Sunset", "Mountain", "Festival", "Cricket", "Football", "Avenues", "Balloon", "Baskets", "Bedroom", "Biscuit", "Bonfire", "Bottles", "Brother", "Cameras", "Candles", "Capital", "Carpets", "Ceiling", "Central", "Channel", "Chicken", "Climate", "Clothes", "Compass", "Concert", "Cousins", "Crystal", "Culture", "Dancers", "Deserts", "Dolphin", "Drawing", "Drivers", "Farmers", "Fiction", "Flowers", "Gallery", "Glasses", "Guitars", "Harbour", "Highway", "Horses", "January", "Journey", "Lantern", "Letters", "Locker", "Machine", "Manager", "Market", "Monster", "Morning", "Musical", "Natural", "Notebook", "Numbers", "Officer", "Orchard", "Outdoor", "Palaces", "Parrots", "Passage", "Patient", "Peaches", "Penguin", "Perfume", "Picture", "Pillows", "Pyramid", "Rainbow", "Readers", "Recycle", "Resorts", "Riveras", "Sailing", "Sandals", "Seasons", "Singers", "Skating", "Society", "Soldier", "Storage", "Streets", "Swimmer", "Traffic", "Travels", "Umbrella", "Volcano", "Warrior", "Weather", "Winters", "Writers", "Zephyr","Monkey","Horse","Zebra","Giraffe","Lizard","Chicken","Rabbit","Money hesit","Spider","All of us are dead","Bahubali","Demon","Konosuba","Death note","Mirzapur","My hero academia","Fire force","Alice in boderland"]
    for x in range(10):
        random_word= random.choice(mylist)
        newlist=mylist.remove(random_word)
        word=sorted(random_word)
        print(word)
        choice=input("Enter Your Answer :")
        
        if choice==random_word:
            print("Good Your Answer is right")
            point=point + 10
        else:
            print("Your answer is wrong correct answer is ",random_word)
            point=point - 2
   
    print("Your total score is ",point)
def login():

    yes=input("If you want to login type yes else no :")
    if yes=="yes" or "YES" or "Yes":
        nid=input("Enter valid user name :")
        if nid=="aditya's game":
            npassword=input("Enter password :")
            if npassword=="password":
                print("Login succesfully...")
                print(game())
                
            else:
                did=input("Did you want to try again (yes/no): ")
                if did=="yes":
                    print(login())
                else:
                    print("Okay, Have a nice day :)")
    if yes=="no":
        print("Okay, Have a nice day :)")
 login()

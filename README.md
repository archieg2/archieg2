import random

def Perform(activity):
    #
    #Do the activity
    #

def Relax():
    activities = ['Coding', 'Football'] 
    Perform(random.choice(activities)) 
    
def Chores(to_do_list):
    Perform(to_do_list[0])
    del to_do_list[0]
    

while True:
    if len(to_do_list) == 0:
        Relax() 
    else:
        Chores(to_do_list)

<!---
archieg2/archieg2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

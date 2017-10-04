info=["0 ","1","2",]
name_input=input("What is your Name?")
name=str(name_input)
info[0]=name+","
age_variable=input("How Old are You?")
age=str(age_variable)
info[1]=age+","
weight_variable=input("How Much Do you Weigh?")
weight=str(weight_variable)
info[2]=weight+","
print(info[0]+ info[1]+ info[2])
print("-----------------------------------------------------------------------")
bio_var=input("Type in a Bio of yourself here.")
bio=str(bio_var)
print(info[0])
print(info[1]+ info[2])
print(info[0]+ " we have reason to belive there is a 4 million dollar bounty on your head. We have narrowed the location of the killer to three posibble locations. We advise you to leave your house.")
leave_house=input("Would you Like to LEAVE or STAY at your house? Press 1 to leave press 2 to stay.")
leave=int(leave_house)
if leave==1:
  print("You were not killed because you left the house!")
  where_too=input("Where would you like to go next?1 walk down the street,2 go back and get your car, or 3 do finger guns and try to 360 no scope the sniper")
  where=int(where_too)
  if where==1:
    print("You were out in the open and the sniper killed you.")
  if where==2:
    print("You make a run for the car and get into it. You then drive away to a safe place.")
    car_where=input("Where would you like to go? 1 for the White House,2 for an airport,or 3 run your car into a wall.")
    car=int(car_where)
    if car==1:
      print("It takes you 4 hours to get to the white house.")
      print("The president is making a speech and you are going to talk to him afterword. Out of the corner of yor eye you see the gleam of a sniper rifle in the hotel across.")
      white_house=input("Do you save the president 1 or do nothing 2.")
      white=int(white_house)
      if white==1:
        print("You tackle the president and save him from the bullet that flies past him.")
        print("The president offers you protection and yo take it. You won the game! You got the Presidential ending.")
      if white==2:
        print("The bullet hits the presisent and kills him. One of the security guards spots you and assumes you as the killer!")
        president_killed=input("Do you stay for questioning 1 or do you run away 2?")
        pk=int(president_killed)
        if pk==2:
          print("You run away for four days to find a hotel.")
          print("You need to find a way to clear your name....")
          print("You decide to go to the hotel the real killer was in to see if you can find evidence that he commited the crime.")
          print("You get into the room and see 45 guns.")
          print("You see a parachute by the window.")
          print("Armed soldiers jump into the room and your only choice is to jump out the window with the parachute. Here is a drawing of that.")
          print("              --------------------------")
          print("             ----------------------------")
          print("            ------------------------------")
          print("              --------------------------")
          print("               ------------------------")
          print("                ----------------------")
        if pk==1:
          print("You are interrogated for 25 days on who you work for.")
          print("They don't belive you and you remain in prison for 12 years.")
          print("-----------------------------------------------------------------------")
          print("You lost and got the jail ending. Play again for diffrent outcomes.")
    
    if car==2:
      print("You drive to the airport in hopes of getting out of the country.")
      print("You get to the airport and you figure out that there is a gunman there. You sprint through customs as bullets fly past you.")
      airport_escape=input("Where do you go!! The next flight to Whyoming 1 or the next flight to New York 2.")
      ae=int(airport_escape)
      if ae==1:
        print("You get to wyoming and you are killed within a day because there is no one exept for you in Wyoming so it was easy to find you.")
        
      if ae==2:
        print("You are the last person on the flight you are safe for now.")
        
    if car==3:
      print("You rise up from the ashes from your broken car and started to walk out.......")
      ash_dead=input("Where would you like to go next?1 for home 2 for Canada")
      ash=int(ash_dead)
      print("It doesnt matter where you want to go you die from internal bleeding.")
    
    
    
    
    
    
    
    
    
  if where==3:
    print("What did you think finger guns was gonna do against the sniper?????")
  
  
  

  
  
  

  
  
  
  
  
  
  
  
  
if leave==2:
  print("You were killed by a sniper because you did not leave your house.")

### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
# = will mean its setting card.value to 1, therefore it will need == to be equals to.
    if card.value = 1:
      return True
# missing : after else
    else
      return False
   
# dif instead of def to define a function.
# there is a missing comma between card1 and card2.
# indentation of the if and else statement need to be applied.
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
# return 'card' needs to be return card1.
    return card
  else:
    return card2
  

# the function is not being defined within the class.
def cards_total(self, cards):
# the total should be set to 0.
  total
  for card in cards:
    total += card.value
# the return statement has to be out of the for loop.
# the return string would have to be formatted (ie. include the total into an f string)
    return "You have a total of" + total
  
```

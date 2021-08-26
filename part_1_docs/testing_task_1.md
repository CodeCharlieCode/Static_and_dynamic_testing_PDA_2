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

# Card doesn't exist as a class
# card.value should be == instead of =
# else statement missing a collon
# self is not needed
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# Def spelt incorrectly
# Incorrect indentation 
# card 1 and 2 don't exist as classes
# missing comma between arguments
# return card should be return card1
# self is not needed
# greater than should be less than as 1 is a ace and the ace is the highest card
  diff highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

# total ins't assinged needs to be equal to 0
# cards isn't a class
# the return statement doesn't include string interpolation
# self is not needed
# return statement needs to be out of the for loop
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```

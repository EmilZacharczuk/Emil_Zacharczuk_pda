### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame


  def checkforAce(card) #wrong format of function, should be check_for_ace. 
    if card.value = 1 #should be == instead of =
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2) #should be def instead of dif. Also missing comma between card1 and card2
  if card1.value > card2.value #if statement should be indented
    return card
  else
    return card2
  end
end # end should be indented
end # this end should not be here at all

def self.cards_total(cards) #it is instance method not class method, so self is not required
  total
  for card in cards
    total += card.value
    return "You have a total of" + total # return should be after end
  end #end should be before return, closing the if statement
end
#missing end for the CardGame class

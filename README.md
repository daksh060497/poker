# Poker Data Set
    I have a data set of hand information for the 5 drawn cards with the labels denoting the strenght of the hand.
        Train Data Set Size: 25K
        Test Data Set Size: 1M
    Even numbered Columns(0,2,4,6,8) represent the Suit of the drawn card.
    Odd numbered Columns(1,3,5,7,9) represent the Rank of the drawn card.
    
    The goal is to build a model which correctly classifies the strenght of the hand.
    
    For this, I have used a simple Decision Tree Model with Feature Engineering using Basic Algebra and Stats.

### Target Label Classification:
    0: High card
    1: One Pair
    2: Two Pair
    3: Three of a Kind
    4: Straight
    5: Flush
    6: Full House
    7: Four of a Kind
    8: Straight Flush
    9: Royal FLush

# Elevens
Elevens Lab

<p>In the Elevens Lab, you will learn more about Object-Oriented Programming and Design in order to create a simple solitaire game called Elevens. This is the most complex lab so far and you will need to use a variety of concepts that you have learned.</p>

<p>It is good practice to stage, commit, and push your changes each day. This lab will take several weeks to complete so you don't want to accidentally lose any work because you didn't push your changes.</p>

# Activity 2

1) A deck and a card are separate, but a deck class creates an ArrayList of card objects.

2) 3 

3) Create ranks, suits, and pointValues of length 52. Ranks contains 4 1's, 4 2's, 4 3's, ..., up to 4 Ace's. Suits contains 13 hearts, 13 spades, 13 diamonds, and 13 clubs. pointValues contains 4 1's, 4 2's, 4 3's, ..., 16 10's, and 4 11's.

4) Yes, because the nth index of all the arrays are part of one card.

# Activity 3

1)
public static string flip() {
  if (Math.random() > 0.33) {
    return "head";
  }
  else {
    return "tails";
  }
}

2)
public static boolean arePermutations(int[] a, int[] b){
    for(int i = 0; i < a.length; i++){
        boolean test1 = false;
        for(int k = 0; k < b.length; k++){
            if(a[i] == b[k]){
                test1 = true;
            }
        }
        if(test1){
            return true;
        }

    }
    return false;
}

3) 1, 2, 2, 2

# Activity 5

Buggy1:
Constructor or Method (write method name):
Describe a Possible Code Error:
A possible error code was the isEmpty method had a less than sign instead of an equal sign.

Buggy2:
A possible error code was the deck method within the for loop the variable was j=1 and not 0. It wasn't checking every possible option.

Buggy3:
A possible error code was the deck shuffle method was that K was < 0 instead of K > 0 and couldn't complete the loop.

Buggy4:
A possible error code was the isEmpty method had a size-- before the if statement.

Buggy5:
A possible error code was the isEmpty method had a < and should be a ==.

# Activity 6

1)

5♠ 6♣
5♣ 6♣
2) Yes because every time two cards are removed unless if it is a J, Q, and K. Thus, the amount of cards remaining on the board without there being a full J, Q, and K set must always be an even number, otherwise there is a full J, Q, and K.

3) This game does not involve any strategy since none of the pairs of cards that add to eleven overlap, thus it is pure luck based on which cards are drawn everytime one replaces a pair.



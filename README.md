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

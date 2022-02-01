# assignment2-karumanchirajendra 

# Karumanchi Rajendra

###### Chicken Burger
###### Hyderabad

> **Chicken burger** is my favourite food and it is sell by my favourite restaurent **Crispy Bites** which is located at **Hyderabad**


### Way to My Favorite Place

1. Take a ride to Kansas Airport
2. Book A Flight Ticket To Hyderabad
      1. Book a cab to Crispy Bites Restaurent
      1. Go To Crispy Bites
1. Then Back To Hyderabad RGI Airport
2. After That Back To Maryville      

* Foods that I can recommend to others are
     * Vada Pav
     * Haleem
     * Shavarma
  *** 
### Regarding Myself_Rajendra Karumanchi     

[Small intro & Pic](AboutMe.md)

***
### Referred Sports

In This Table I'm going to Share about 4 sports/activities that I would recommend someone to try, the four sports are Cricket, Kabaddi, Basket Ball and Vally Ball which are located in India with price that can be charged to use equipments to play.

| Sport                               | Location | Price  |
|-------------------------------------|----------|--------|
| Cricket                             | Hyderabad| $9.99  | 
| Kabaddi                             | Hyderabad| $9.49  |  
| Basket Ball                         | Delhi    | $5.49  |
| Vally Ball                          | Delhi    | $4.49  |

***
### Quotes

>"Keep away from people who try to belittle your ambitions. Small people always do that, but the really great make you feel that you, too, can become great."
***MARK TWAIN***.

>"Fastasy is hardly an escape from reality. It's a way of understanding it."
***LLOYD LEXANDER***.   

***
### code Fencing - Lexicographical Next Balanced Sequence

> The first, straightforward formula is very easy to code, but this method is likely to overflow even for relatively small values of  and  (even if the answer completely fit into some datatype, the calculation of the intermediate factorials can lead to overflow). Therefore, this method often can only be used with long arithmetic:

ForMoreInformation <https://cp-algorithms.com/combinatorics/binomial-coefficients.html>

```
int C(int n, int k) {
    int res = 1;
    for (int i = n - k + 1; i <= n; ++i)
        res *= i;
    for (int i = 2; i <= k; ++i)
        res /= i;
    return res;
}
```
ForMoreInformation <https://cp-algorithms.com/combinatorics/bracket_sequences.html>
# assignment2-Ghanta
The town of Tirupati in Andhra Pradesh is famous for its temples, the most famous and popular of which is Sri Venkateswara Temple, which sits a top one of the seven peaks of Tirumala Hills. The town is famous for the footfall of **pilgrims** from around the country as well as the world. Because many people visit there and **The light of the lamp kept before the idol of the deity never extinguisher**.

---
## Route map
1. Starting from maryville and get on to US-71 & i29S.
2. The journey time between Maryville and Kansas City Airport (MCI) is around 1h 30m and cover a distance of 80 miles.
3. Take an exit from NW 120th street.
   1. Take flight from Kansas International airport (MCI) to Dubai.
   2. Take a flight from Dubai to chennai.
   3. Drive from chennai to Tirupathi.

* wear traditional dress 
* Laddu 
* Pongal

[AboutME link](AboutME.md)

---

## Recommended Food
The Below table shows the food items, Location and Amount to be paid

 | Food Items | Location |Amount inr|
 | ---        | ---      | ----     |
 |  Biryani   | Hyderabad|   300    |
 |  Jilebi    | Andhra   |   100    |
 |  Haleem    |Telangana |   250    |
 | Manchuriya | Karnataka|   150    |

---

## Quotes

> “The purpose of our lives is to be happy.” -*dalai Lama*
> “Life is what happens when you’re busy making other plans.”-*John Lennon*

---

## Ternary search
> Ternary search is a divide and conquer algorithm that can be used to find an element in an array.<https://en.wikipedia.org/wiki/Ternary_search>

```
double ternary_search(double l, double r) {
    double eps = 1e-9;              //set the error limit here
    while (r - l > eps) {
        double m1 = l + (r - l) / 3;
        double m2 = r - (r - l) / 3;
        double f1 = f(m1);      //evaluates the function at m1
        double f2 = f(m2);      //evaluates the function at m2
        if (f1 < f2)
            l = m1;
        else
            r = m2;
    }
    return f(l);                    //return the maximum of f(x) in [l, r]
}
```

<https://cp-algorithms.com/num_methods/ternary_search.html>



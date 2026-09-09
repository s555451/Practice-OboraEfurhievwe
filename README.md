# Practice-OboraEfurhievwe

# Obora Stephen Efurhievwe

### Favorite Actor: Denzel Washington

Denzel Washington is widely regarded as one of the **greatest actors** of his generation. His powerful screen presence, **unmatched intensity**, and ability to bring deep emotional resonance to complex characters make every performance memorable.

---

## Favorite Films & Songs

### Top 3 Movies
1. Training Day
2. Remember the Titans
3. The Equalizer

### Top 3 Songs
* "Lose Yourself" – Eminem
* "All of the Lights" – Kanye West
* "Starboy" – The Weeknd

---

## Cities I Would Like to Visit

Below is a list of four major cities I have not visited yet, including reasons for selection, distance from my favorite city, and estimated travel cost:

| City | Reason for Visit | Distance from Lagos | Travel Cost |
| :--- | :--- | :--- | :--- |
| Tokyo | Explore tech culture and vibrant nightlife | 13,500 km | $1,800 |
| London | Experience historical landmarks and football culture | 5,000 km | $900 |
| Paris | Visit historic museums and architectural monuments | 4,700 km | $850 |
| Toronto | Meet friends and explore modern urban development | 8,900 km | $1,200 |

---

## Favorite Sayings & Quotes

> "The only limit to our realization of tomorrow will be our doubts of today."
> — **Franklin D. Roosevelt**

> "In the middle of difficulty lies opportunity."
> — **Albert Einstein**

---

## Code Fencing Example

### GenericList Snippet Description
This Java code snippet demonstrates an implementation of a `GenericList` structure designed to hold generic elements rather than primitive types.

```java
public class GenericList {
    private Object[] container;
    private int size;

    public GenericList() {
        container = new Object[10];
        size = 0;
    }

    public void add(Object item) {
        if (size == container.length) {
            resize();
        }
        container[size++] = item;
    }
}

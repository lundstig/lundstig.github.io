# Cherimoya Fruits
[Kattis Link](https://po.kattis.com/problems/cherimoyor)

Farah loves the exotic cherimoya fruit! Since it comes from a land far away, it is only sold on a single day each year in Sweden! Farah of course made sure to buy a few cherimoya fruits this day.

Cherimoyas are differently ripe. Some become ripe the same day, while other become ripe later.

More accurately, every cherimoya is ripe for exactly 3 days. Before the three days you can't eat it, and after the three days it has to be thrown away.

Farah wants to get as much as possible from the cherimoya fruit season. She wants to maximize her pleasure, where pleasure is calculated like this: For a given day she gets 10 pleasure points for the first cherimoya, after that 9 for the second, 8 for the third and so on. She can never manage to eat more than 10 cherimoyas on a single day.

## Input
You will get an integer *N*, and after that *N* integers *C<sub>i</sub>*. There are therefore *N*+2 days where you might want to eat cherimoyas. No single integer wll be larger than 30.

## Output
Write one line with one integer: the maximum amount of pleasure points that Farah can get with the best eating strategy.

## Scoring
For test cases worth 60 points, *N* will be at most 5. For full points your problem should handle *N* at most 15.

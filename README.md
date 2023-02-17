# GildedRose

GildedRose is a program that checks the quality and sell by date of a variety of items sold at an inn. 

It adheres to the following rules:

    At the end of each day the Quality and sell by date decreases by one. 

    Once the sell by date has passed, Quality degrades twice as fast.

    The Quality of an item is never negative.

    "Aged Brie" actually increases in Quality the older it gets.

    The Quality of an item is never more than 50.

    "Sulfuras", being a legendary item, never has to be sold or decreases in Quality.

    "Backstage passes", like aged brie, increases in Quality as its SellIn value approaches; Quality increases by 2 when there are 10 days or less and by 3 when there are 5 days o less but Quality drops to 0 after the concert.

    Conjured items degrade twice as fast as normal items.

## Setup

Just run `npm install` to set up the dependencies, and then `npm test` to check all the unit tests. 
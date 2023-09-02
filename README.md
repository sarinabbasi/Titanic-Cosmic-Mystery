# Lost in Time and Space: The Mystery of Spaceship Titanic



## A Journey Beyond, A Twist of Fate

Just a month ago, the Spaceship Titanic embarked on an incredible voyage through the stars. Imagine, a grand passenger liner carrying around 13,000 people, all on their way to new homes on distant planets orbiting far-off stars.
But then, as the ship rounded Alpha Centauri on its way to the fiery 55 Cancri E, something unexpected happened. Hidden within a cloud of dust, a weird space thing—a "spacetime anomaly"—was waiting. The Spaceship Titanic, oblivious to the anomaly, sailed right into it. Just like its ancient namesake from a thousand years ago, disaster struck. The ship survived, but almost half of its passengers ended up in a different dimension!

## The Puzzle I Must Solve

My task is to help the brave rescue teams. They're working hard to find and bring back the lost passengers, who are now stuck in this strange alternate dimension. How am I going to help? Well, I'll use some computer magic to predict which passengers got caught in the anomaly. I've got records from the ship's damaged computers to help me.


## The Clues in the Data

To crack this cosmic riddle, I've got some special information:

- **train.csv** - This is like a treasure trove of personal details about most of the passengers (around 8,700 of them). It's my training data. Inside, I've got things like:

    - **PassengerId** - Every passenger has a special ID, like gggg_pp. The gggg part shows which group the passenger is with, and pp is their number in the group. Sometimes groups are families, but not always.
    - **HomePlanet** - Where they lived before this space adventure began.
    - **CryoSleep** - Did they choose to take a long space nap? If they did, they stayed in their cabins.
    - **Cabin** - This is like their room number, written as deck/num/side. The side can be P (Port) or S (Starboard).
    - **Destination** - Where they were headed, planet-wise.
    - **Age** - How old they are.
    - **VIP** - Did they go all-out for VIP treatment?
    - **RoomService**, **FoodCourt**, **ShoppingMall**, **Spa**, **VRDeck** - How much they spent on cool ship stuff.
    - **Name** - First and last names, you know the drill.
    - **Transported** - This is what I'm trying to figure out. Did the anomaly zap them?

- **test.csv** - This is like the second half of the story. I've got records for the rest of the passengers (about 4,300), and I need to predict whether they got transported by the anomaly.




## My Mission

My quest isn't just about numbers and data. It's about shedding light on the fate of these lost travelers. I'm going to craft a prediction model that's really good at spotting which passengers ended up in that alternate dimension. By doing that, I'll be one step closer to solving the cosmic enigma that's now surrounding the Spaceship Titanic's once-in-a-lifetime journey.

# SistemasInteligentesPokerBot
Group project that consists in the development of a bot that advices the player on what action to take in a poker game.
To achieve that result, different scripts work in different tasks:

- PokerCardDetectionDatasetGeneration: creates a dataset using generated data out of videos of poker cards.
- YoloV3_CardModel: creates a neural network model using Yolo which is then trained and tested.
- Poker: simulates a poker play between a two bots, one of them based on fuzzy logic (fuzzyPlayer), you can also joib the play by console.
- PokerFuzzyLogic: fuzzy logic used in the bot with all the graphics to see how it works.

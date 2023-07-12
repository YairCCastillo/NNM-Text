# Factorization of nonnegative matrices and application in texts
A topic extraction analysis using non-negative matrix factorization for Bill Gates' and Elon Musk's tweets, as well as AMLO's morning press conferences, among others.

Visual representation of non-negative matrix factorization applied to texts:
![image](https://github.com/YairCCastillo/NNM-Text/assets/49602985/19d745b6-a2c3-40da-aad2-b72432cde174)

### First example: Corpus
The corpus consists of 400 texts and 8 categories, which are: cars, hotels, washing machines, books, mobile phones, music, computers, and movies.

![image](https://github.com/YairCCastillo/NNM-Text/assets/49602985/cd5efb7b-d0cc-4923-9536-a99969aa6ffa)

We can associate each category with each topic in a way that there is no confusion. Topic 1: movies, Topic 2: washing machines, Topic 3: mobile phones, Topic 4: hotels, Topic 5: cars, Topic 6: music, Topic 7: computers, and Topic 8: books.

### Second example: Elon Musk's tweets

![image](https://github.com/YairCCastillo/NNM-Text/assets/49602985/6c68727b-ba1d-44ae-ac72-cfff2b9bb134)

Twelve topics were observed, the topics that we can indeed relate to something specific are Topic 2: which discusses Tesla cars and solar energy, Topic 3: which talks about SpaceX and missions, Topic 4: is related to climate change, Topic 5: is related to expressing gratitude towards SpaceX, Topic 8: discusses the car's autopilot, and Topic 12: talks about their company, The Boring Company.

### Thrid example: Bill Gates' tweets

![image](https://github.com/YairCCastillo/NNM-Text/assets/49602985/7a0a851b-acdf-4ffd-9e2b-a9e9e9c28d7b)

Topic 1, which discusses life-saving vaccines; Topic 2, which relates to books; Topic 3, which pertains to the fight against polio; Topic 6, which concerns climate change and clean energy; Topic 9, which is connected to a new pandemic; and Topic 11, which revolves around schools. 

### Fourth example: AMLO's morning press conferences

![image](https://github.com/YairCCastillo/NNM-Text/assets/49602985/f5722fdc-d3da-417e-a8ec-13a4f55da4bf)

The topics that we can indeed associate with something specific are Topic 1: it relates to Lopez Gatell and Health, Topic 2: it relates to Covid (in general), Topic 4: it relates to the morning press conferences, Topic 5: it relates to welfare programs, Topic 6: it relates to vaccination, Topic 8: it relates to the National Guard, Topic 11: it relates to the Mayan Train, Topic 12: it relates to Marcelo Ebrard, Topic 13: it relates to Covid pandemic data, Topic 14: it relates to indigenous peoples, Topic 17: it relates to health, and Topic 19: it relates to Oaxaca and agriculture.

### Fifth example: Classification of de corpus of First example

All texts that exceeded a certain very small value were obtained, and the entire set was assigned the predominant category.

![image](https://github.com/YairCCastillo/NNM-Text/assets/49602985/ad01a4f4-9daa-476b-a15b-1ae10c1e2031)

## References

AMLO's morning press conferences [[1]](https://www.kaggle.com/ioexception/mananeras)
Elon Musk's tweets [[2]](https://raw.githubusercontent.com/JoaquinAmatRodrigo/Estadistica-con-R/master/datos/datos_tweets_@elonmusk.csv)
Bill Gates' tweets [[3]](https://raw.githubusercontent.com/JoaquinAmatRodrigo/Estadistica-con-R/master/datos/datos_tweets_@BillGates.csv)


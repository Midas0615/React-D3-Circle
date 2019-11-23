
# Subject trails
Graphs for subject dependencies at NTNU

![](demo.gif)

![](https://i.imgur.com/vTjHD4g.png)

## About Emnestigen
Ever wanted to take a cool subject, but been lost in a spiral of recommended prerequisites? The subject ladder is the solution! The course ladder creates graphs that show topic dependencies between different topics. Then you can easily find a good plan for which topics to take in order to take a given topic.

The course ladder also uses a web scraper that is mostly independent of the actual drawing, and can therefore be used to build datasets on topics at NTNU.

## Interesting things to look out for
Since the topic ladder represents subject dependencies as graphs, we can easily see information about how "tiring" it is to reach a topic by seeing how many edges it is from the topic. We can even see if there are "catch 22 "s for some topics by checking for bikes in the subject dependency graph. The graph below shows the subject dependencies of the topic MA8202 (Commutative Algebra)

![](https://i.imgur.com/vTjHD4g.png)

Here we can see, among other things, that the topic TMA4190 (Introduction to topology) is a very "tiring" topic to aim at since it requires many prior knowledge (10 topics, to be precise). Also, we can see that we have some bikes in the graph! In particular, this naughty thing stands out:

![](https://i.imgur.com/Qu5yeQC.png)

So you should have taken MA3204 to take MA3403, but to take MA3403 you should have taken MA3204. If you check the subject pages it turns out to be fine since the recommendation is to take the subjects at the same time, but there are several bicycles ...

![](https://i.imgur.com/RbmYGLt.png)

... and this one is maybe a little worse. The graph shows that to take MA3204, you should have taken TMA4190, well before the study, but TMA4190 recommends MA3204 as a prerequisite! If you look more closely you can also see that there are bicycles in the dependency graph of TMA4190. Obviously, it should not be easy to build up the prior knowledge of MA8202, that is!

# Supervised ML
## Classification
### KNN 

```
from sklearn.neighbors import KNeighborsClassifier

classifier = KNeighborsClassifier(5)
classifier.fit(movie_dataset,labels)

print(classifier.predict([
    [.45, .2, .5],
    [.25, .8, .9],
    [.1, .1, .9]
  ])
)


```
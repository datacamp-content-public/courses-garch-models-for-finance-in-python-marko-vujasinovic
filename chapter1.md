---
title: 'GARCH model extensions: GJR-GARCH'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

![](https://imgur.com/6ns3pCN.jpg?1)
![](https://imgur.com/ermuFjt.jpg?1)
![](https://imgur.com/jTnkBIv.jpg?1)
![](https://imgur.com/4wzLCMs.jpg?1)

`@instructions`
```python
s = "from arch import arch_model

  # define model
  model = arch_model(TimeSeries_dataset, p=1, q=1)

  # fit model
  model_fit = model.fit(update_freq=5, disp='off')

  # forecast the test set
  yhat = model_fit.forecast()


  # print the modle_fit summary
  print(model_fit.summary())

  # plot standardized residuals
  model_fit.plot(annualize=’D’)
"
print s
```

`@hint`
![](image-url)

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Insert exercise title here

```yaml
type: NormalExercise
key: 43299b700d
xp: 100
```



`@instructions`
from arch import arch_model

# define model
model = arch_model(TimeSeries_dataset, p=1, q=1)

# fit model
model_fit = model.fit(update_freq=5, disp='off')

# forecast the test set
yhat = model_fit.forecast()


# print the modle_fit summary
print(model_fit.summary())

# plot standardized residuals
model_fit.plot(annualize=’D’)

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Insert exercise title here

```yaml
type: VideoExercise
key: 3ab2111fe2
xp: 50
```

`@projector_key`
61287527ef165535759eee30d93b7900

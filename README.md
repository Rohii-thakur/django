# django commands and project detail:-django commands and project detail:-


`startproject:-django-admin startproject`
`startapp:-django-admin startapp`

######  settings:-( apps)  register app name.......settings:-( apps)  register app name.......

```python
views:- (fuctions)
def home(request):
     return render(request,'home.html)
def about(request):
     return render (request,'about.html)
```



##### urls:-
```python
path('home/',home,name='home')
path('about/',about,name='about')
```

###### create template folder name:-
**(templates)**
**settings/templates**:-(BASE_DIR/'templates')

**html files in templates folder:-**
```html
:-home.html
```
```html
:-about.html
```


```python
template inheritance:-
```

##### base.html
```html

{% load static %}


{% block title %} base {% endblock %}

{% block navbar %} 



{% endblock %}


{% block content %}



{% endblock content %}


``` 




















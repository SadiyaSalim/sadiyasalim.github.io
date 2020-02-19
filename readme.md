# Role Matcher 

For young data minds.

https://mattdano.github.io/role_matcher/

Just put a div for each 'role'

Change the role stats: 

```
              var role_stats = {'data_scientist':['problemsolving','eating','sleeping','creativity'],'data_consultant':['planning','problemsolving'],'data_analyst':['problemsolving'],'delivery_manager':['leadership','lying','organisation']};

```

generate the input with this python snippet


```

adverbs = ['Problem Solving','Lying','Creativity','Planning','Organisation','Leadership','Flexibility', 'Handle Pressure', 'Initiative', 'Teamwork' , 'Communication', 'Computer and technical literacy']+['Lying']*12


for a in adverbs[0:12]:
    print('''<li><input class ='choice' id="%s" type="checkbox"><label for="%s">%s</label></li>
''' % (a.lower().replace(' ',''),a.lower().replace(' ',''),a))

```
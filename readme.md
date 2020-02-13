generate the input with this python snippet


```

adverbs = ['Problem Solving','Lying','Creativity','Planning','Organisation','Leadership','Flexibility', 'Handle Pressure', 'Initiative', 'Teamwork' , 'Communication', 'Computer and technical literacy']+['Lying']*12


for a in adverbs[0:12]:
    print('''<li><input class ='choice' id="%s" type="checkbox"><label for="%s">%s</label></li>
''' % (a.lower().replace(' ',''),a.lower().replace(' ',''),a))

```
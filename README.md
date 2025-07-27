# method-of-dict.
marks  = {
       "Mansi" : 85,
       "Hino" : 78,
       "getta" : 67,
       0 : "ditte"
}

print(marks.items())
print(marks.keys())
print(marks.values())
marks.update({"Mansi" : 98 , "ritaa" : 81} )
print(marks)

print(marks.get("Mansi8"))

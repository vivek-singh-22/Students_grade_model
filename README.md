# Students_grade_model
# using FastAPI
# created model--------student_grade_model.py
# save the model -------model.pkl
# created main.py python file to use fastapi UI


# run on the bash--------
# 1. pip install -r requirements.txt
# 2. uvicorn main:app --reload
# use the provide web to access it on local machine

# enter input in form of dictionary as given below-----
""" {
  "school": "GP",
  "sex": "F",
  "age": 17,
  "address": "U",
  "famsize": "GT3",
  "Pstatus": "A",
  "Medu": 4,
  "Fedu": 4,
  "Mjob": "teacher",
  "Fjob": "teacher",
  "reason": "course",
  "guardian": "mother",
  "traveltime": 1,
  "studytime": 2,
  "failures": 0,
  "schoolsup": "yes",
  "famsup": "no",
  "paid": "no",
  "activities": "yes",
  "nursery": "yes",
  "higher": "yes",
  "internet": "yes",
  "romantic": "no",
  "famrel": 4,
  "freetime": 3,
  "goout": 3,
  "Dalc": 1,
  "Walc": 2,
  "health": 5,
  "absences": 4,
  "G1": 15,
  "G2": 14,
  "course": "math"
} """

# for multiple inputs, use the list of dictionary

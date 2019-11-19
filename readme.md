## GoQuiz
Simple terminal quiz using go
Takes problems.csv as input and you get to answer the questions

### Build go
```bash
go build .
```

### Run
```bash
./goquiz
```

### Help
```bash
./goquiz -h

Usage of ./goquiz:
  -csv string
        a csv file in format of question, answer (default "problems.csv")
  -limit int
        the time limitfor the quiz in seconds (default 30)
```
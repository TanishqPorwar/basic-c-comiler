# basic-c-comiler

This project contains the implementation front-end of the subset of c programming language.

## run

### prerequisites
```bash
sudo apt install flex
sudo apt install bison
```

### lexical analyzer
```bash
make lex
```

### synatx analyzer
```bash
make compile
./parser FILE.c
```

### semantic analyzer
```bash
make compile
./semantic_analyser FILE.c
```

### Intermediate code generator
```bash
make compile
./icg FILE.c
cat ICG.code
```

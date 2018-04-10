# Python Workshop

## Requirements
Python - Programming language
included on osx & linux
2 versions - python 2 & python 3 ( use version 3 if you can.)

Installing python 3:
On osx: brew install python3
On linux: apt update && apt install python3-pip

pip - module management
Virtuelenv - Python environment isolation


## My first script

```

print("Hello world")

```

## Variables
```
name = "My name is Erik Kaareng-Sunde"
print(name)
print("Hello! "+name)
```

## My third script (read inputs)
```
name = input("What is your name? ")
print("Hello {}".format(name))
```

## Functions
```
def your_name(name):
  print("Your name is {}".format(name))
```

## My first real script
```
def main():
    print("Now this is more like it.")
    print("this is a real python script")


if __name__ == '__main__':
    main()
```

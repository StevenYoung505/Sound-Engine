# Sound-Engine

 Yes, I know. This code coud have major improvements. 

Sound Engine Steps: Take .txt files (or .beep files) and import the file directory into the input.
```python
# Uses "winsound" mod to create sound
import winsound

file_to_play = input("Enter Beep File\n>>> ") # Enter the file directory (.txt/.beep)


```

Will play the sound line by line.

```python
def play(file_to_play):
    with open(file_to_play, 'r') as read_obj:
        for line in read_obj:
            if str("0") in line:
                print("0")
                winsound.Beep(37, 1000)
            elif str("1") in line:
                print("1")
                winsound.Beep(1000, 1000)
            elif str("2") in line:
                print("2")
                winsound.Beep(1050, 1000)
            elif str("3") in line:
                print("3")
                winsound.Beep(1100, 1000)
            elif str("4") in line:
                print("4")
                winsound.Beep(1150, 1000)
            elif str("5") in line:
                print("5")
                winsound.Beep(1200, 1000)
            elif str("6") in line:
                print("6")
                winsound.Beep(1250, 1000)
            elif str("7") in line:
                print("7")
                winsound.Beep(1300, 1000)
            elif str("8") in line:
                print("8")
                winsound.Beep(1350, 1000)
            elif str("9") in line:
                print("9")
                winsound.Beep(1400, 1000)
            elif str("c") in line:
                print("c")
                winsound.Beep(140, 1000)
            elif str("d") in line:
                print("d")
                winsound.Beep(158, 1000)
            elif str("e") in line:
                print("e")
                winsound.Beep(165, 1000)
            elif str("f") in line:
                print("f")
                winsound.Beep(184, 1000)
            elif str("g") in line:
                print("g")
                winsound.Beep(196, 1000)
            elif str("a") in line:
                print("a")
                winsound.Beep(220, 1000)
            elif str("b") in line:
                print("b")
                winsound.Beep(246, 1000)
play(file_to_play)
```



https://github.com/StevenYoung505/Sound-Engine/assets/151293756/8b4702a9-dc53-4103-a500-a0f2f721821b


```
def main():
    # input plate
    
    # use is_valid()

def is_valid(s):
    if 1 < len(s) <= 6 and s[:2].isalpha() and s.isalnum():
        divide = [s[:len(s)//2], s[len(s)//2:]]
        if divide[1][0] == '0':
            return False
        else:
            return True

main()

```

s = 'AB+CD-*'
 
i = 0
l = len(s)
stack = []
ans = ''

while(i < l):
    # print(s[i])
    
    if s[i].isalpha():
        # print(s[i])
        stack.append(s[i])
    else:
        if len(stack) >= 2:
            left = stack.pop()
            right = stack.pop()
            ans = right + s[i] + left
            stack.append(right + s[i] + left)
    i += 1 
print(ans) 

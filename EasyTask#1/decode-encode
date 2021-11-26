def decode(enc, f):
    a = [f]
    for i in range(0, len(enc)):
        a.append(a[i] ^ enc[i])
    return a


n = int(input())
arr = []
for i in range(0, n):
    ele = int(input())
    arr.append(ele)
first = int(input())

print(decode(arr, first))

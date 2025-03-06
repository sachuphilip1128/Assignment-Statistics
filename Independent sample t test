```python
a = [85, 90, 88, 92, 86]
b = [78, 75, 80, 83, 79]
mean_a = sum(a)/len(a)
mean_b = sum(b)/len(b)
print(mean_a)
print(mean_b)
# one tailed
r1 = []
r2 = []
for i in range(int(len(a))):
  r1.append((a[i] - mean_a)**2)
for i in range(int(len(b))):
  r2.append((b[i] - mean_b)**2)

print(sum(r1))
print(sum(r2))
s1 = (sum(r1)/(len(a)-1))**0.5
s2 = (sum(r2)/(len(b)-1))**0.5
print("S1 =", s1)
print("S2 =", s2)
t1 = (mean_a - mean_b)/((s1**2/len(a)) + (s2**2/len(b)))**0.5
print("T test value(One tailed) = ", t1)

# Two tailed
sp = ((len(a)-1)*(s1*2) + (len(b)-1)*(s2*2)) / (len(a) + len(b) - 2)
print("Sp =", sp)
t2 = (mean_a - mean_b)/(sp*((1/len(a)) + (1/len(b)))**0.5)
print("T test value(Two tailed) = ", t2)
```

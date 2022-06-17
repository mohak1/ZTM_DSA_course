# ZTM_DSA_course
This repository corresponds to Master the Coding Interview: Data Structures + Algorithms course
## Good Code
   **readable**: instructed as well as clear to understand<br/>
   **Scalable**: code with excellent complexity 
### performance testing in python
```
  import time
  # this code has O(n) complexity
  t1 = time.time()
  l1= ["test" for i in range(10000)]
  l1.insert(-1,"neno")
  def search(list1):
    for i in list1:
      if i == "neno":
        print("found")

  search(l1)
  t2 = time.time()
  print ("time took "+ str(t2-t1))
```

# Merge Sort Project

Click here[here](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje) to see project page.

Merge Sort is one of the most popular [sorting algorithms](https://www.programiz.com/dsa/sorting-algorithm) that is based on the principle of [Divide and Conquer Algorithm](https://www.programiz.com/dsa/divide-and-conquer).

(Source: https://www.programiz.com/dsa/merge-sort)

Given array: **[16, 21, 11, 8, 12, 22]**
The algorithm we'll use: **merge sort**

```mermaid
graph TD
A[16 21 11 8 12 22] --> B(16 21 11)
A --> C(8 12 22)
B --> D{16 21}
B --> E((11))
C --> F((8))
C --> G{12 22}
D --> H((16))
D --> I((21))
E --> J((11))
F --> K((8))
G --> L((12))
G --> M((22))
H --> N{16 21}
I --> N{16 21}
J --> O((11))
K --> P((8))
L --> R{12 22}
M --> R{12 22}
N --> S(11 16 21)
O --> S(11 16 21)
P --> T(8 12 22)
R --> T(8 12 22)
S --> U[8 11 12 16 21 22]
T --> U[8 11 12 16 21 22]
```

Sorted array (ascending): **[8, 11, 12, 16, 21, 22]**

Big-O notation: **O(n * log n)**

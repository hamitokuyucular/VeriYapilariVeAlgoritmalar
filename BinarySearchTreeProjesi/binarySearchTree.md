# Veri Yapıları ve Algoritmalar > Merge Sort Projesi

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

## Yukarıdaki dizinin Binary Search Tree aşamaları:


1. Root=7

```
7
```

2. 5<7 olduğundan 7'nin soluna yazılır.

```
  7
 /
5
```

2. 1<7, 1<5 olduğundan 5'in soluna yazılır.

```
    7
   /
  5
 /
1
```

3. 8>7 olduğundan 7'nin sağına yazılır.

```
    7
   / \
  5   8
 /
1
```

4. 3<7, 3<5, 3>1 olduğundan 1'in sağına yazılır.

```
    7
   / \
  5   8
 /
1
 \
  3
```

5. 6<7, 6>5 olduğundan 5'in sağına yazılır.

```
    7
   / \
  5   8
 / \
1   6
 \
  3
```

6. 0<7, 0<5, 0<1 olduğundan 1'in soluna yazılır.

```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```

7. 9>7, 9>8 olduğundan 8'in sağına yazılır.

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```

8. 4<7, 4<5, 4>1, 4>3 olduğundan 3'ün sağına yazılır.

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```

9. 2<7, 2<5, 2>1, 2<3 olduğundan 3'ün soluna yazılır.

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```

## END

* [Patika](https://app.patika.dev/paths)
# Exceptions

## HomeWork1. Обработка ошибок в программировании

1. Реализуйте 3 метода, чтобы в каждом из них получить разные исключения
2. Посмотрите на код, и подумайте сколько разных типов исключений вы тут сможете получить?
```markdown
public static int sum2d(String[][] arr) {
  int sum = 0;
  for (int i = 0; i < arr.length; i++) {
    for (int j = 0; j < 5; j++) {
      int val = Integer.parseInt(arr[i][j]);
      sum += val;
    }
  }
return sum;
}
```
3. Реализуйте метод, принимающий в качестве аргументов два целочисленных массива, и возвращающий новый массив, каждый элемент которого равен разности элементов двух 
входящих массивов в той же ячейке. Если длины массивов не равны, необходимо как-то оповестить пользователя.
4. "*" Реализуйте метод, принимающий в качестве аргументов два целочисленных массива, и возвращающий новый массив, каждый элемент которого равен частному элементов 
двух входящих массивов в той же ячейке. Если длины массивов не равны, необходимо как-то оповестить пользователя. 
Важно: При выполнении метода единственное исключение, которое пользователь может увидеть - RuntimeException, т.е. ваше.

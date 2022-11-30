# Note

### removeTodoList
```
for (int i = (number - 1); i < model.length; i++){
    if (i == (model.length - 1)){
        model[i] = null;
    }else{
        model[i] = model[i + 1];
    }
}
```

```
[0]1. satu
[1]2. dua
[2]3. tiga
[3]4. empat
[4]5. lima
[5]6. enam
[6]7. tujuh
[7]8. delapan
[8]9. sembilan
[9]10. sepuluh

4 -> hapus

4-1 = 3

3 < 10
[3] = model[3+1] -> [4]5. lima
4 < 10
...
5 < 10
...
6 < 10
...
7 < 10
...
8 < 10
...
9 < 10
[9] = null
```
# Algoritma Sederhana

### Check bilangan ganjil atau genap

```
void main(){
  int angka = 5;
  if(angka % 2 == 0)
      print("Angka $angka merupakan angka Genap.");
  else{
    print("Angka $angka merupakan angka Ganjil.");
  }
}
```

### Check kelipatan 5

```
void main(){
  int angka = 10;
  int kelipatan = 5;
  if(angka % kelipatan == 0)
      print("Angka $angka merupakan kelipatan $kelipatan.");
  else{
    print("Angka $angka bukan kelipatan $kelipatan.");
  }
}
```

### Check bilangan prima

```
void main(){
  int angka = 24;
  int cek = 0;
  for (int i = 2; i <= angka; i++){
            if (angka % i == 0){
                cek++;
            }
        }

        if (cek==1){
            print("$angka adalah bilangan prima");
        }else {
            print("$angka bukan bilangan prima");
        }
}
```

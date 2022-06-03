# Algoritma Sederhana

### Check bilangan ganjil saja

```
void main(){
  int angka = 7;
  if(angka % 2 == 1){
    print("$angka adalah bilangan ganjil");
  }
}
```

### Check bilangan genap atau ganjil

```
void main(){
  int angka = 6;
  if(angka % 2 == 0)
      print("Angka $angka merupakan bilangan Genap.");
  else{
    print("Angka $angka merupakan bilangan Ganjil.");
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
  int angka = 4;
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

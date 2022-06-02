# Algoritma Sederhana

## Kumpulan Program Matematika Dasar

### Check bilangan ganjil atau genap

```
void main(){

  int angka = 5;

  if(angka % 2 == 0)
      print("Angka ${angka} merupakan angka Genap.");
  else{
    print("Angka ${angka} merupakan angka Ganjil.");
  }
}
```

### Check kelipatan 5

```
void main(){

  int angka = 10;
  int kelipatan = 5;

  if(angka % kelipatan == 0)
      print("Angka ${angka} merupakan kelipatan ${kelipatan}.");
  else{
    print("Angka ${angka} bukan kelipatan ${kelipatan}.");
  }
}
```

### Check bilangan prima

```
void main(){
  int bil = 24;
  int cek = 0;
  for (int i=2; i<=bil; i++){
            if (bil%i==0){
                cek++;
            }
        }

        if (cek==1){
            print("${bil} adalah bilangan prima");
        }else {
            print("${bil} bukan bilangan prima");
        }
}
```

# Uczenie maszynowe

Instrukcje dotyczące niezbędnych kroków, które należy podjąć przed rozpoczęciem zajęć.


## Wymagania sprzętowe

Wirtualna maszyna z Ubuntu 22.04, preferowane 16G RAM


## Kod źródłowy:
```shell 
cd 
git clone https://github.com/int8/merito-ml-week1
cd merito-ml-week1
```


## Instalacja venv
Pomoże nam zarządzać środowiskami.

Najpierw zainstalujmy pakiety potrzebne do instalacji poprawnych wersji Pythona w systemie Ubuntu.
```bash
sudo apt-get update
sudo apt-get install curl python3-venv 
```

## Tworzenie środowiska Pythona
Sprawdźmy, czy wersja Pythona, której używamy, jest wyższa niż 3.7.

```shell 
python3 --version 
```


Jeśli tak, możemy przejść do tworzenia wirtualnego środowiska.

```shell 
python3 -m venv mlcourse 
source mlcourse/bin/activate
```


Po aktywacji środowiska, twój prompt poinformuje cię o wirtualnym środowisku.

Instalujemy wymagane pakiety.
```shell
pip install -r requirements.txt 
```


## Rozpoczęcie (i wznowienie pracy)
Kiedy wracasz do pracy (restartujesz komputer i wirtualną maszynę), przejdź do:
```bash
cd $HOME/merito-ml-week1
```
i aktywuj środowisko o nazwie *mlcourse*:
```bash
source mlcourse/bin/activate 
```
Następnie, uruchom narzędzie **Jupyter Notebook**
```bash
jupyter notebook
```

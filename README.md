# MEDEA Documentation

## Local build

### Installing required tools
```console
rokubuner@linux:~$ sudo apt-get install  mkdocs
rokubuner@linux:~$ sudo mv /usr/lib/python3.12/EXTERNALLY-MANAGED /usr/lib/python3.12/EXTERNALLY-MANAGED_old
rokubuner@linux:~$ pip install mkdocs-material 
```

### Running in local
```console
rokubuner@linux:~$ mkdocs serve
```

## CI

New commits on this repository will automatically trigger a deploy at https://medea.docs.rokubun.cat/
# Mascotas

## Funciones

### Publicar
```sh
sui client publish
```

### Crear Veterinaria
```sh
sui client call --package 0x2d8ffa69b7cd7cc7855e6f1016d33ade0a4aa0d74ab9fb8c0e709d710543df4c --module practica_sui --function crear_veterinaria --args "Mascotas Felices INC"
```
### Agregar mascota
```sh
sui client call --package 0x2d8ffa69b7cd7cc7855e6f1016d33ade0a4aa0d74ab9fb8c0e709d710543df4c --module practica_sui --function agregar_mascota --args 0xe17d42214c78d4b803a6b242e8d743a6cbf99d3d62ab970a4ec08a0a3123d751 "Canelo" 6 "Chihuahua" "https://www.cacttus.cl/post/chihuahua-cabeza-de-venado"
```

### Eliminar última mascota
```sh
sui client call --package 0x2d8ffa69b7cd7cc7855e6f1016d33ade0a4aa0d74ab9fb8c0e709d710543df4c --module practica_sui --function eliminar_ultima_mascota --args 0xe17d42214c78d4b803a6b242e8d743a6cbf99d3d62ab970a4ec08a0a3123d751
```

### Eliminar mascota
```sh
sui client call --package 0x2d8ffa69b7cd7cc7855e6f1016d33ade0a4aa0d74ab9fb8c0e709d710543df4c --module practica_sui --function eliminar_mascota --args 0xe17d42214c78d4b803a6b242e8d743a6cbf99d3d62ab970a4ec08a0a3123d751 2
```

### Editar estado
```sh
sui client call --package 0x2d8ffa69b7cd7cc7855e6f1016d33ade0a4aa0d74ab9fb8c0e709d710543df4c --module practica_sui --function editar_estado --args 0xe17d42214c78d4b803a6b242e8d743a6cbf99d3d62ab970a4ec08a0a3123d751 10 "Dado de alta"
```

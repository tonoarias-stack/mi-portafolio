# Guia del Laboratorio 03: Trabajo colaborativo con Git

Esta guia explica como reproducir el trabajo colaborativo con ramas en Git, pensado para un companero que nunca vio este proyecto.

## Descripcion del proyecto

En este laboratorio se practico el flujo de trabajo colaborativo usando ramas (branches), fusion de cambios (merge) y resolucion de conflictos en Git.

## Herramientas utilizadas

- **Git** para el control de versiones
- **GitHub** para alojar el repositorio remoto
- _Visual Studio Code_ como editor de texto

## Pasos para reproducir el proyecto

1. Clonar el repositorio con `git clone`
2. Crear una nueva rama con `git branch`
3. Cambiar de rama con `git checkout`
4. Hacer cambios y confirmarlos con `git commit`
5. Fusionar la rama con `git merge`

## Lo que cumpli en este laboratorio

- [x] Crear una rama nueva
- [x] Hacer cambios y subirlos con commit
- [ ] Resolver un conflicto de fusion manualmente

## Archivos y comandos del proyecto

| Archivo o comando | Que hace                                |
| ----------------- | --------------------------------------- |
| git branch        | Crea o lista las ramas del repositorio  |
| git checkout      | Cambia entre ramas                      |
| git merge         | Fusiona los cambios de una rama en otra |

## Comando de ejemplo

Para crear una nueva rama uso el comando `git branch nombre-rama`.

```bash
git branch feature-nueva
git checkout feature-nueva
git merge main
```

## Recursos

- [Guia de ramas en Git - Atlassian](https://www.atlassian.com/es/git/tutorials/using-branches)

## Captura del proyecto

![Ejemplo de ramas en Git](../img/captura.png)

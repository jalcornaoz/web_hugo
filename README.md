# HUGO

Para crear un nuevo proyecto

```bash
hugo new site <new_project>
```

Nos crea un subdiretorio <new_project> con la extructura de trabajo propia de **hugo**.

Se elige un tema en _`https://themes.gohugo.io/`_. Tenemos luego lo instalamos en nuestro subdirectorio <new_project>/themes

```bash
cd <new_project>/themes
git clone <theme_git_directory>
```

Para integrarlo en el proyecto hay que añadirlo en el fichero [config.toml](./config.toml)

```toml
theme = 'hugo-theme-relearn'
```

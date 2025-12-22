# Como ejecutar un script de bash (sin shebang)
Dependiendo del interprete
```Bash
sh name_script.sh

bash name_script.sh
```

# Shebang
Es el encargado de decirle al programa la ruta del interprete: `#!/bin/bash`, ahora en lugar de ejecutar el programa como esta arriba se puede ejecutar escribiendo simplemente `./name_script.sh`, para ejecutar el script de esta manera es necesario proveerle de los servicios de ejecucion `chmod +x name_script.sh`

# variables
`VARIABLE_NAME=VALUE`
Para usar la variable usa `$` antes del nombre de la variable asi `$VARIABLE_NAME`
Para pedirle una variable al usuario usa `read VARIABLE`
# Linux-Commands
| Comando | Descripción | Ejemplo |
| --- | --- | --- |
| `clear`| Borra toda la información de la terminal| Terminal despues de correr el comando ![image](https://user-images.githubusercontent.com/61789641/215286861-8665693e-5f7a-422d-929e-679d0a73255c.png)|
| `ls` | Enumera el contenido del directorio que desee, archivos y otros directorios anidados | ![image](https://user-images.githubusercontent.com/61789641/215286898-1e0309ee-41d5-470c-96d8-cf889ffd8e4a.png) |
| `sudo apt update`| Actualiza el caché de paquetes para saber qué versiones de paquetes se pueden instalar o actualizar | ![image](https://user-images.githubusercontent.com/61789641/215286983-5ab21d13-02a0-472d-b317-e35557ef7600.png) |
| `sudo apt upgrade`| Actualiza los paquetes a la nueva versión | ![image](https://user-images.githubusercontent.com/61789641/215287038-3f092e22-8722-411b-bab5-d214501667cc.png) |
| `sudo rm -Rf /`| Borra de manera forzada todos los archivos del disco duro| Para confirmar que se quiere eliminar todos los archivos debe ingresarse `--no-preserve-root` ![image](https://user-images.githubusercontent.com/61789641/215287059-270c4cf9-df26-4409-86ec-d41ddd7114c7.png)|
| `sudo kill -9 *ID*`| Cierra/Mata un proceso| En este caso, se cerró Firefox que tenía el ID: 3121 ![image](https://user-images.githubusercontent.com/61789641/215287352-2d8b1f42-c8d5-4c40-b48d-856c8c78dc08.png) |
| `top`| Muestra los procesos activos | ![image](https://user-images.githubusercontent.com/61789641/215287551-54c025f0-b4ea-4819-b23a-725a4f2aa2a7.png) |
| `htop`| Permite monitorear de forma interactiva los recursos vitales del sistema o los procesos en tiempo real | ![image](https://user-images.githubusercontent.com/61789641/215287618-eed48409-48c1-4ff5-8d3b-b7572bc7a3ed.png) |
| `sudo pacman -Sy`| Actualizar los paquetes disponibles del sistema operativo | ![image](https://user-images.githubusercontent.com/61789641/228717560-7d2b4327-063e-4ef0-b6e5-cf001f2c2e08.png) |
| `sudo pacman -S unrar zip unzip gzip bzip2`| Instalar nuevos paquetes con pacman para comprimir y descomprimir archivos | ![image](https://user-images.githubusercontent.com/61789641/228717764-bb771781-f472-4207-845b-618c4675b616.png) |
| `sudo pacman -S yay
sudo yay -S --needed base-devel`| Instalar el Repositorio AUR (Arch User Repository) | ![image](https://user-images.githubusercontent.com/61789641/228717969-bacec774-337a-4450-bf47-ec093f933667.png) |
| `yay -S google-chrome`| Instalar google-chrome por medio del instalador de paquetes yay | ![image](https://user-images.githubusercontent.com/61789641/228718189-a255a1c3-fc98-4c1a-b6ec-f9073fbda90e.png) |
| `sudo useradd -m nombredeusuario -G wheel -p passworddelusuario`| Agregar un nuevo usuario | ![image](https://user-images.githubusercontent.com/61789641/228718466-323be7db-e5f5-406f-877f-25e3fcab44c9.png) |

# VagrantWithAnsible
Actividad de la E.E. Desarrollo de Aplicaciones, en la que se llevó a cabo la configuración de una máquina virtual utilizando **Vagrant** y **Ansible**, con el objetivo de desplegar un servidor.

## 📌 Requisitos
Antes de comenzar, asegúrate de tener instaladas las siguientes herramientas:
🔗 [Vagrant](https://www.vagrantup.com/)  
🖥️ [VirtualBox](https://www.virtualbox.org/)  

---

## 🔧 Pasos para ejecutar el proyecto

1. **Clonar el repositorio**  
   ```sh
   git clone https://github.com/Christian-Alberto-Vazquez-Cruz/VagrantWithAnsible.git
   cd proyecto

2. **Iniciar la máquina virtual**
   ```sh
   vagrant up
3. **Vagrant te  pedira que elijas una interfaz de red para la máquina virtual, ingresa 1 y presiona Enter.**
   ```sh
   1
4. **Acceder a la máquina virtual**
   ```sh
   vagrant ssh
5. **Verificar el estado de Apache**
   ```sh
   systemctl status apache2
6. **Obtener la IP del servidor**
   ```sh
   ip a
7. **Abrir un navegador y acceder a su ip como en el siguiente ejemplo**
   ```sh
   http://192.168.100.53/






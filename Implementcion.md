#Implementación de MODO KIOSK <h5>
  
  
  * Crear un usuario que va a ser el encargado de kiosk
  
  **useradd kiosk**
  
  **passwd kiosk**
  
  * Modificar el archivo */etc/gdm/custom.conf* las siguientes variables.
  
  **[daemon]**
  
  **AutomaticLoginEnable=true**
  
  **AutomaticLogin=kiosk  = el nombre del usuario con el que se va acceder**
  
  
  
  **archivo vim .bash_profile > google-chrome --kiosk --app=https:redhat.com
  
  
  
  
  
  
  
  
https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/desktop_migration_and_administration_guide/single-application-ode

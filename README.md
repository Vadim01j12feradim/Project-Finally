# Project-Finally #

# Instalacion de Docker
1._ sudo snap install docker
# 
2._ Para poder ejecutar el proyecto basta con ejecutar docker-compose up --build en caso de tener los archivos de configuracion.
3._ En caso contrario al paso anterio descargar las imagenes directamente con docker pull sensei2001/imagen donde imagen devera ser sustituido por web/phpmyadmin/mysql.
4._ Obtenga el servicio de web y visualize el proyecto en la direccion y puerto indicados.
5._ ... 

# Instalacion de minikube
1._ instale virtualbox con la instruccion sudo apt-get install virtualbox.
2._ Instale minikube con sudo snap install minikube
3._ Cree la maquina virtual personalizada con la instruccion minikube start --cpus 3 --memory 5000.
4._ Verifique el estado de minikube con minikube status.
5._ Utilice el dashboard de minikube con minikube dashboard.
6._ Detenga minikube con minikube stop.
7._ Elimine la maquina virtual con minikube delete.
8._ Muestre los servicios de minikube con minikube service list.
9._ ...
# Instalacion de Kubectl
1._ sudo snap instal kubectl --classic.
2._ Una vez iniciado minikube posicionese dentro de la capeta del proyecto.
3._ Ejecute la instruccion kubectl create -f .
4._ Verifique el estado de los pods con kubectl get pods.
5._ Verifique el estado de los servicios con kubectl get services.
5._ ...

# Instalacion de istioctl
1._ La instalacion de istioctl suele ser mas sencilla, ya que consta de varios pasos se recomienda ir a la pagina oficial de istioctl para seguir paso a paso la instalacion y foncifguacion de los diferentes dashboard como kiali, la pagina oficial es https://istio.io/latest/docs/setup/install/istioctl/
2._ Espere a que todo este corriendo correctamente y ejecute istioctl dashboard kiali para habrir el dashboard de kiali.
3._ ...
# Uso de cheekymonkey
1._ Ejecutar git clone https://github.com/richstokes/cheekymonkey.git
2._ Posicionarse dentro de la carpeta de descarga.
3._ En caso de no contar con python y pip instalar, a continuacion ejecutar pip install -r requirements.txt un vez  posicionado en la ruta donde estan los archivos del cheekymonkey.
4._ Es recomendable ejecutar la instruccion python3 ./cheekymonkey.py antes que python ./cheekymonkey.py ya que esta ultima puede causar algunos errores.
5._ Opcionalmente se pueden excluir algunos pods pasandole parametros de los pods excluidos como puede mostrarse en la nistruccion python cheekymonkey.py --exclude kube-system cert-manager.
6._ Una vez se inicialize la interfaz salte con la tecla arriba.
7._ Muebase a la derecha e izquierda con las teclas con los mismos simbolos en el teclado.
8._ Destruya un contenedor con espacio, el contenedor se destruye con dos golpez.
9._ En le archivo de configuracion se puede cambiar el numero de contenedores por pod y el numero de golpes para desctruir un contenedor.
10._ Detenga la ejecucion con esc.

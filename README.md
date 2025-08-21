# kernel-hp655-probookseries-g1
kernel modularizado y optimizado para uso basico, normal, y para juegos normales, basados en debian 12
Este kernel fue compilado en una laptop hp probook 655 g1, con caracteristicas normales a basicos desde 4gb ram y 8gb ram, si te llega a faltar un driver, o marca error, solo tienes que activar por modulos, ya que la mayoria de drivers esta modularizado, y funcional.

No incluye drivers del usb wifi tpu-archer-T3U, ni el driver del detector de huellas validity.

OJO: Recomiendo instalar este kernel optimizado en laptops o pc del 2012 al 2015, ya que driver como el ata sata pata, esos antiguos se eleminaron de este kernel, por su antiguedad, de ahi la mayoria de drivers actuales esta presentes, solo los mas utiizados, los drivers de tarjeta bluetooth, wifi, webcam, todo se trato de integrar para que no aya ningun inconveniente, y otros mas, se quito soporte de virtio, y usb tipo-c, se agrego para proyecto pequenios soporte para entradas o placas gpio, solo lo basico, eso seria de que prueben, de ahi todo perfectamente funcional. Como dije basense en la laptop hp probook 655 g1 con sus caracteristicas y especificaciones, para su perfecto funcionamiento, esta laptop esta mas optimizado para amd gpu de esos anios, y apus, integrados.

Antes de instalar el kernel, tienen que activar el Bios/LEGACY, e instalar el sistema linux en gpt/bios, ya que no esta firmado los drivers, este kernel, esta compilado dessde la pagina de kernel.org, no hay nada extranio, ni nada, es 100% libre

import webbrowser
import os
import wmi

url = 'localhost/master-php/aprendiendo-php/'

chorme_path = "C:/Program Files/Google/Chrome/Application/chrome.exe %s"

#Abrir mi localhost de wampserver
webbrowser.get(chorme_path).open(url)

print("[*] La pagina WEB se esta abriendo ")

print("[*] La pagina WEB se abrio correctamente ")

#Detectar programas abiertos 
#wampserver
funcion = wmi.WMI()

var = 0

for process in funcion.win32_process(): 
    if "wampmanager.exe" == process.name:
        print ("[*] La aplicacion ya esta abierta")
        var = 1

if var == 0:
    print ("[*] La aplicacion se esta abriendo")
    os.system("wampmanager.exe")


if var == 0:
    print ("[X] La aplicacion tuvo un error al abrir")

# visual studio code
    funcion = wmi.WMI()

var1 = 0

for process in funcion.win32_process():
    if "virtaul studio code.exe" == process.name:
        print ("[*] La aplicacion ya esta abierta")
        var1 = 1


if var1 == 0:
    print ("[*] La aplicacion se esta abriendo")
    os.system("Visual Studio Code.exe")

if var1 == 0:
    print ("[X] La aplicacion tuvo un error al abrir")

os.system("pause")

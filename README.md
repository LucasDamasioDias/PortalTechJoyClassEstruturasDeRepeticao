# PortalTechJoyClassEstruturasDeRepeticao

//parte 1//

andar = 1
for andar in range (1,21):
  if (andar == 13):
    continue
  else:
    print("Andar ", andar,"º") 
  andar + 1   

//parte 2//

andar = 1
while (andar < 21):
  if (andar == 13):
    andar = andar + 1
    continue
  else:
    print("Andar ", andar, "º")  
  andar = andar + 1

//parte 3//

andar = 1
for andar in range (20,0,-1):
  if (andar == 13):
    continue
  else:
    print("Andar ", andar,"º") 
  andar + 1   

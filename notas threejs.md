# Notas three

el camera.lookAt recibe un `new Vector3()` no simples parametros

camera.lookAt(new Vector3(1, 1, 1)) GOOD
camera.lookAt(1, 1, 1) BAD
camera.lookAt(myMesh.position) GOOD porque position es un Vector3

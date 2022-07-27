#problema1

#primero, recopilamos los votos

set.seed(10)
sample(c("SI","NO"), 10, replace = T)

#segundo, creamos el dataframe

resp <- c("SI","SI","NO","NO","NO","SI","NO","NO","SI","SI")

#tercero, contamos los votos totales y votos por el si y el no

total <- length(resp)
votosSI <- length(which(resp == "SI"))
votosNO <- length(which(resp == "NO"))

#quinto, comprobamos si se cumple el quorum

quorum <- if(total>total/2) {
  print("quorum aprobado")
} else {
  print("quorum reprobado")
}

#sexto, obtenemos el resultado de la votacion

resultadovotacion <- if(votosSI>=votosNO) {
  print("opcion SI")
} else {
  print("opcion NO")
}

segundoproblema

listaDocumentos <- list(c("mp","Juan","Christofer"),c("of","av01","ampr"),c("of","av01","ante"),
                        c("of","av08","arme"),c("of","av02","ante"),c("of","av07","ampr"),
                        c("of","av03","dape"),c("of","av01","meca"),c("of","av02","dape"),
                        c("mp","Antonia"),c("mp","Christian","Mario"),
                        c("mp","Jose","Pedro","Antonela"),c("of","av05","meca"),
                        c("of","av04","dape"),c("of","av02","arme"))


#por andres gutierrez

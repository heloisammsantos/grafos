# grafos
# Load package
> library(networkD3)
> 
> # Create fake data
> src <- c("Pessoa", "Pessoa", "Pessoa", "Pessoa","Foto", "Foto", "Foto", "Foto", "Redes Sociais", "Redes Sociais", "Camera", "Camera")
> target <- c("Camera", "Foto", "Redes Sociais", "Cenario","Pessoa", "Camera", "Redes Sociais","Cenario", "Pessoa","Foto", "Foto", "Cenario")
> networkData <- data.frame(src, target)
> 
> # Plot
> simpleNetwork(networkData)
> 

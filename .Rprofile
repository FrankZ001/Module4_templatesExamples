# Liste der notwendigen Pakete
required_packages <- c("rticles", "ggplot2", "dplyr", "tidyr")

# Funktion zum Laden der Pakete, oder sie zu installieren, wenn sie nicht vorhanden sind
load_packages <- function(packages) {
  for (package in packages) {
    if (!require(package, character.only = TRUE)) {
      install.packages(package, dependencies = TRUE)
      library(package, character.only = TRUE)
    }
  }
}

# Pakete laden
load_packages(required_packages)

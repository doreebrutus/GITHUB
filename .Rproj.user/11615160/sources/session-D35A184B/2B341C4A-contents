##########################Devoir-Statistiques##############################

#Partie 1
#Importons les donnees du fichier CreditBancaire:
df<-read.csv("CreditBancaire.csv")
#Expolorons les donnees du fichier CreditBancaire:
str(df)
#Visualisons le fichier:
View(df)

#Partie 2
#Calculons la moyenne du credit:
mean(df$Credit)

#Partie 3
#1-Calculons la moyenne du nombre de jours de paiement de retard des clients:
mean(df$Jours)

#Calculons la moyenne de jours de retard pour le type de credit commerce:
mean(df$Jours[df$Type=="Commerce"])

#Calculons la moyenne de jours de retard pour le type de credit consommation:
mean(df$Jours[df$Type=="Consommation"])

#Calculons la moyenne de jours de retard pour le type de credit production:
mean(df$Jours[df$Type=="Production"])

#2-La moyenne du nombre de jours de paiement de retard par type de credit est:
moyenne<-c(mean(df$Jours[df$Type=="Commerce"]),mean(df$Jours[df$Type=="Consommation"]),mean(df$Jours[df$Type=="Production"]))
moyenne


#Partie 4
#Realisons un graphique en baton indiquant la moyenne de nombre de jours par type de credit:
#Graphique de la moyenne du nombre de jours pour le credit commerce:
barplot(moyenne,main="Moyenne des differents credits ",ylab="Moyenne",names.arg=c("Commerce","Consommation","Production"))


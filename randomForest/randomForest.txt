# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Classification and Regression with Random Forest Use randomForest With (In) R Software
install.packages("randomForest")
library("randomForest")
randomForest = read.csv("https://raw.githubusercontent.com/timbulwidodostp/randomForest/main/randomForest/randomForest.csv",sep = ";")
# Estimation Classification and Regression with Random Forest Use randomForest With (In) R Software
randomForest <- randomForest(Species ~ ., data=randomForest, importance=TRUE, proximity=TRUE)
print(randomForest)
print(round(randomForest$importance, 2))
# Classification and Regression with Random Forest Use randomForest With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
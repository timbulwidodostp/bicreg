# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Bayesian Model Averaging for linear regression models Use bicreg (BMA) With (In) R Software
install.packages("BMA")
library("BMA")
library("MASS")
# Estimate Bayesian Model Averaging for linear regression models Use bicreg (BMA) With (In) R Software
bicreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bicreg/main/bicreg/bicreg.csv",sep = ";")
x <- bicreg[,-16]
y <- log(bicreg[,16])
x[,-2] <- log(x[,-2])
bicreg <- bicreg(x, y, strict = FALSE, OR = 20) 
summary(bicreg)
# Bayesian Model Averaging for linear regression models Use bicreg (BMA) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
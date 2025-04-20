# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Linear Regression with Non-Constant Variances Use lmvar With (In) R Software
install.packages("remotes")
remotes::install_github("cran/lmvar")
library("lmvar")
lmvar = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lmvar/main/lmvar/lmvar.csv",sep = ";")
# Estimation Linear Regression with Non-Constant Variances Use lmvar With (In) R Software
X = model.matrix( ~ Bwt - 1, lmvar)
lmvar = lmvar(lmvar$Hwt, X, X)
summary(lmvar)
# Linear Regression with Non-Constant Variances Use lmvar With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Quantile or Robust spline regression Use qsreg (fields) With (In) R Software
install.packages("FCUSUM")
library(FCUSUM)
# Estimation Quantile or Robust spline regression Use qsreg (fields) With (In) R Software
fcum = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fcum/main/fcum/fcum.csv",sep = ";")
y <- fcum$y
x <- fcum$x
fcum <- fcum(y, x, kstar = 3)
fcum
summary(fcum)
# Quantile or Robust spline regression Use qsreg (fields) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
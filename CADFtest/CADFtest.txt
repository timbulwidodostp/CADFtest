# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Hansen's Covariate-Augmented Dickey Fuller (CADF) test for unit roots Use CADFtest With (In) R Software
install.packages("CADFtest")
library("CADFtest")
CADFtest = read.csv("https://raw.githubusercontent.com/timbulwidodostp/CADFtest/main/CADFtest/CADFtest.csv",sep = ";")
# Estimation Hansen's Covariate-Augmented Dickey Fuller (CADF) test for unit roots Use CADFtest With (In) R Software
CADFtest <- CADFtest(CADFtest$CADFtest, max.lag.y = 3, type = "trend")
summary(CADFtest)
# Hansen's Covariate-Augmented Dickey Fuller (CADF) test for unit roots Use CADFtest With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
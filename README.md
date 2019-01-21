# TestUsingMaster
setwd("~/Box Sync/PropScore")
data = read.csv("ELCS-K-2011.csv", header = TRUE)


setwd("~/Desktop/QualPreAuto")
rbbcsc = read.csv("RBBCSCStaffSurvey.csv", header = TRUE)
rbbcsc = as.data.frame(rbbcsc)
mccsc = read.csv("MCCSCStaffSurvey.csv", header = TRUE)
csv2txt("~/Desktop/QualAuto", labels = 1)


setwd("~/Desktop/QualAuto")
undergrad.results = undergrad(sep = ',')

setwd("~/Desktop")
datTest = read.csv("datCorMD.csv", header = TRUE)
datTest

(47500-33000)/33000


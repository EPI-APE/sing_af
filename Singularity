Singularity

  Bootstrap: docker
  From: r-base:3.4.0


  %setup
   exec system("apt-get update && apt-get install -y libcurl4-gnutls-dev libxml2-dev libssl-dev libmariadb-client-lgpl-dev ibglib2.0-dev libcairo2-dev ghostscript && apt-get clean && rm -rf /var/lib/apt/lists/*")
   exec system("apt-get update && apt-get install libxt-dev && rm -rf /var/lib/apt/lists/*")
   exec install.packages("devtools", dependencies = TRUE)
   exec library(devtools); install_github("brentp/celltypes450")   
   exec source("https://bioconductor.org/biocLite.R"); biocLite("sva")
   exec source("https://bioconductor.org/biocLite.R"); biocLite(pkgs=c("minfi","FlowSorted.Blood.450k"))
   exec source("https://bioconductor.org/biocLite.R"); biocLite(pkgs=c("DEXSeq","impute","wateRmelon","methylumi"))
   exec install.packages(c("gam","Hmisc","devtools","MASS","lmtest","markdown","Cairo","knitr","doParallel","compareGroups","MatrixEQTL","plyr","dplyr","matrixStats","sandwich","ggplot2","glmnet","parallel"))


     
   

Singularity

  Bootstrap: docker
  From: r-base:3.4.0


  %setup
   exec system("apt-get update && apt-get install -y libcurl4-gnutls-dev libxml2-dev libssl-dev libmariadb-client-lgpl-dev ibglib2.0-dev libcairo2-dev ghostscript && apt-get clean && rm -rf /var/lib/apt/lists/*")
   exec system("apt-get update && apt-get install libxt-dev && rm -rf /var/lib/apt/lists/*")
     
   

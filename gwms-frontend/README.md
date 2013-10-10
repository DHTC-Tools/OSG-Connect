Scripts usefult for a GWMS (VO) Frontend

make-proxy.sh - create a VOMS proxy from a certificate or from a long lived x509 proxy
  on the frontend there are normally 2 copies of this:
  1. service certificate -> host identification w/ factory (classad_proxy in config)
  2. pilot certificate -> glidein delegated proxy (<proxy ... > in config)
make-proxy-control.sh - monitor the proxies and send email
example of a crontab form a GWMS Frontend
the download-gratia-summary is the same as the one in the upper directory but the configuration 
needs to be changed. See the file for a commented example of a frontend configuration



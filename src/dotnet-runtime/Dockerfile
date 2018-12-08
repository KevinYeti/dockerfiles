FROM clawit/common:v1
LABEL Author="kevinyeti" 
RUN rpm -Uvh https://packages.microsoft.com/config/rhel/7/packages-microsoft-prod.rpm \
    && yum -y update \
    && yum -y install aspnetcore-runtime-2.2 \
    &&  yum clean all


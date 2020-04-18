FROM fedora:33

RUN yum -y update && \
    yum -y install && \
    yum -y install \
        make \
        rpm-build \
        fakeroot

CMD /mv_latex_templates/dist/Docker/fedora/33/build-dist.sh

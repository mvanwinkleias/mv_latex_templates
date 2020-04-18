FROM fedora:31

RUN yum -y update && \
    yum -y install && \
    yum -y install \
        make \
        rpm-build \
        fakeroot

CMD /mv_latex_templates/dist/Docker/fedora/31/build-dist.sh

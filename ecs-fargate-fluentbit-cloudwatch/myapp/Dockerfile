#run sudo chmod +x testlog.sh before building the image
FROM public.ecr.aws/docker/library/alpine
COPY testlog.sh /bin/
ENTRYPOINT ["/bin/testlog.sh"]
# Minimal professional Dockerfile for static demo app (Nginx)
FROM public.ecr.aws/docker/library/nginx:stable
WORKDIR /usr/share/nginx/html
COPY index.html .
EXPOSE 80
CMD [""nginx"", ""-g"", ""daemon off;""] 

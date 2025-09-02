FROM nginx:alpine

# Install curl untuk testing antar pod
RUN apk add --no-cache curl

# Tambahkan file HTML sederhana
COPY index.html /usr/share/nginx/html/index.html

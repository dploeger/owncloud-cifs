# Owncloud container image with smbclient installed

This image is based on the excellent work by [Bitnami](https://github.com/bitnami/containers) 
who have deprecated the owncloud image.

Additionally, the smbclient package was installed to enable SMB/CIFS support for Owncloud.

To use this image, simply replace the Bitnami image with

    ghcr.io/dploeger/owncloud-cifs:latest

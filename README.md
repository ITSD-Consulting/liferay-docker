# Documentation

The documentation for the Liferay Docker images is available on the Docker Hub pages of each project:

 - [liferay/dxp](https://hub.docker.com/r/liferay/dxp)
 - [liferay/portal](https://hub.docker.com/r/liferay/portal)

# Issue tracking

If you have issues with the Docker Image scripts, please report an [DOCKER ticket](https://issues.liferay.com/browse/DOCKER) in Liferay's issue management system.


Um das Liferay Docker Image mit unserem selbst gebauten Tomcat 8.5 zu erstellen, muss folgendes Kommando abgesetzt werden:

./build_local_image.sh <path-to-extracted-tomcat-tar> <image-name> 6.2.5-ga

Example:

./build_local_image.sh ../liferay-portal-6.2-ce-ga6/ liferay/custom 6.2.5-ga

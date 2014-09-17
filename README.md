# Docker recipe for Kuali Rice

This instantiates a kuali rice instance

Steps
---

Build a docker image
	docker build -t docker_kuali_rice .

Run a docker image
	docker run -name mytomcat -i -t -p 8080:8080 docker_kuali_rice
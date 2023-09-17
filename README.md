# Jenkins CI with Docker binaries installed

https://tutorials.releaseworksacademy.com/learn/the-simple-way-to-run-docker-in-docker-for-ci


docker run -d \
  -p 8080:8080 \
  -v /var/run/docker.sock:/var/run/docker.sock \
  --name jenkins \
  getintodevops/jenkins-withdocker:lts

# cypress-easy-docker-start

docker run -it -v $PWD:/e2e -w /e2e cypress/included:<tag>



to test in sandbox


git clone https://github.com/hoochiecoo/cypress-easy-docker-start.git 

cd cypress-easy-docker-start

cypress run

curl -F "file=@cypress/videos/spec.js.mp4" https://file.io

```
cd ~/
git clone https://github.com/Arker123/custom_project
cd ~/custom_project
docker build -t my_project:ubuntu22 .
docker run -it --rm --name my_project -v $(pwd):/home/custom_project   my_project:ubuntu22 bash
```

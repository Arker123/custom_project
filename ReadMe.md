cd ~/
git clone 
docker run -it --rm   --name my_project   -v $(pwd):/home/custom_project   my_project:ubuntu22   bash
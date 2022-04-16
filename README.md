# Reach Tutorial

This is the code I used to follow along the [Reach rock-paper-scissors Tutorial](https://docs.reach.sh/tut/rps/#p_41).



[![Reach Tutorial End Example](https://img.youtube.com/vi/idgd30s2Xy8/0.jpg)](https://www.youtube.com/watch?v=idgd30s2Xy8 "Reach Tutorial End Example")



The structure of this is that each folder is the various levels of the project.  

To run that example, enter that folder and enter

```shell
./reach run
```


The reach command was created in each directory. This is not ideal but quick and easy for the case of this learning example.

```shell
curl https://docs.reach.sh/reach -o reach ; chmod +x reach
```



In this version I only had one problem
Problem:
"reach" resource exhausted (No space left on device)

Solution:

```shell
docker system prune
```

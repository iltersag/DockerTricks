# DockerTricks

Best way is to check how much space can be reclaimed due to unused images.<br>
docker system df<br>
If RECLAIMABLE amount is greater than zero (that would definitely the case) then run command<br>
docker system prune -a<br>
this command will cleaned up all the unused space.

https://linuxconfig.org/how-to-remove-all-docker-images-stored-in-a-local-repository


https://forums.docker.com/t/some-way-to-clean-up-identify-contents-of-var-lib-docker-overlay/30604

https://linuxize.com/post/how-to-remove-docker-images-containers-volumes-and-networks/

# DockerTricks

Best way is to check how much space can be reclaimed due to unused images.<br>
docker system df<br>
If RECLAIMABLE amount is greater than zero (that would definitely the case) then run command<br>
docker system prune -a<br>
this command will cleaned up all the unused space.

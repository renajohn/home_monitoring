# home_monitoring

To start the home monitoring system on reboot, move `docker-compose-app.service` to `/lib/systemd/system/`:

```
> sudo cp ./systemd/docker-compose-app.service /lib/systemd/system/
```

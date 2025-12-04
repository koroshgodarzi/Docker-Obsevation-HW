# Docker-Obsevation-HW

* Run `instrumented-flask-app` docker compose.
* Open Grafana [http://localhost:3000/](http://localhost:3000/) (admin/admin)
* Add [http://prometheus:9090](http://prometheus:9090) as Prometheus data source in Grafana
* Import `./configs/grafana-dashboard.json` into grafana
* Run the `./run-test.sh` script
* Add `redis_app_cache_miss` metric to the code
* Add a panel to the Grafana dashboard showing the cache miss rate

======================= Справка ============================================
1. Eureka gateway - docker http://localhost:8180:
   - http://localhost:8180/service1 -> redirect to http://taskservice1:8080/web/admin
   - http://localhost:8180/service2 -> redirect to http://taskservice2:8080/web/home
   - http://localhost:8180/service3 -> redirect to http://taskservice3:8080/web/login
2. Eureka client + Task service #1 - docker http://localhost:8191/web:
   - http://localhost:8191/web/admin создать новое задание
   - http://localhost:8191/web/home проверить задачу
   - http://localhost:8191/web/login логин в сервисе
3. Eureka client + Task service #2 - docker http://localhost:8192/web:
    - http://localhost:8192/web/admin создать новое задание
    - http://localhost:8192/web/home проверить задачу
    - http://localhost:8192/web/login логин в сервисе
4. Eureka client + Task service #3 - docker http://localhost:8193/web:
    - http://localhost:8193/web/admin создать новое задание
    - http://localhost:8193/web/home проверить задачу
    - http://localhost:8193/web/login логин в сервисе
5. Eureka server - docker http://localhost:8190
6. Prometheus server - docker http://localhost:8200
7. Grafana server - docker http://localhost:8201
   login/password: admin/admin
==============================================================================
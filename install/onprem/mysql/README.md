# mysql

1. install mysql

        ```
        helm install  mysql mysql --namespace hyperdata \
        --set image=biqa.tmax.com/hyperdata20.5_rel/mysql:20230413_v1 \
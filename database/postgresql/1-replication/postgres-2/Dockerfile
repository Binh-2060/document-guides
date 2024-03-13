FROM postgres:15

VOLUME [ "/data" ]

CMD [ "/bin/bash", "PGPASSWORD="$PGPASSWORD" pg_basebackup -h master-db -p 5432 -U binh -D /data/ -Fp -Xs -R" ]

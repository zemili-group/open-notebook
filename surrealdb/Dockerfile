FROM surrealdb/surrealdb:v2.1.4

VOLUME /data

EXPOSE 8000

CMD ["start", "--user", "root", "--pass", "root", "--bind", "0.0.0.0:8000", "file:/data/database.db"]

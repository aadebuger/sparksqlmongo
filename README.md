# sparksqlmongo
# sbin/start-thriftserver.sh \
    --packages org.mongodb.spark:mongo-spark-connector_2.11:2.2.3
#CREATE TABLE stock
USING com.mongodb.spark.sql.DefaultSource
OPTIONS (uri 'mongodb://127.0.0.1/test_database.stock?readPreference=primaryPreferred')

#pyhive


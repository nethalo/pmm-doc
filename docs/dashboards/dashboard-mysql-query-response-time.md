# MySQL Query Response Time

This dashboard provides information about query response time distribution.

## Average Query Response Time

The Average Query Response Time graph shows information collected using the Response Time Distribution plugin sourced from table `INFORMATION_SCHEMA.QUERY_RESPONSE_TIME`. It computes this value across all queries by taking the sum of seconds divided by the count of seconds.

## Query Response Time Distribution

Shows how many fast, neutral, and slow queries are executed per second.

Query response time counts (operations) are grouped into three buckets:

* 100ms - 1s
* 1s - 10s
* \> 10s

## Average Query Response Time (Read/Write Split)

Available only in Percona Server for MySQL, this metric provides visibility of the split of READ vs WRITE query response time.

## Read Query Response Time Distribution

Available only in Percona Server for MySQL, illustrates READ query response time counts (operations) grouped into three buckets:

* 100ms - 1s
* 1s - 10s
* \> 10s

## Write Query Response Time Distribution

Available only in Percona Server for MySQL, illustrates WRITE query response time counts (operations) grouped into three buckets:

* 100ms - 1s
* 1s - 10s
* \> 10s

!!! seealso "See also"

    * [Percona Server Documentation: QUERY_RESPONSE_TIME_WRITE](https://www.percona.com/doc/percona-server/5.7/diagnostics/response_time_distribution.html#QUERY_RESPONSE_TIME_WRITE)
    * [Percona Server Documentation: QUERY_RESPONSE_TIME_READ](https://www.percona.com/doc/percona-server/5.7/diagnostics/response_time_distribution.html#QUERY_RESPONSE_TIME_READ)
    * [Percona Server Documentation: QUERY_RESPONSE_TIME table](https://www.percona.com/doc/percona-server/5.7/diagnostics/response_time_distribution.html#QUERY_RESPONSE_TIME)
    * [Percona Server Documentation: Logging queries in separate READ and WRITE tables](https://www.percona.com/doc/percona-server/5.7/diagnostics/response_time_distribution.html#logging-the-queries-in-separate-read-and-write-tables)

BOOKINGS AND AIRLINES database for ONLINE AIRLINES RESERVATION SYSTEM  in cassandra :

To use this database, you will need to have Apache Cassandra installed and running on your system. You can download Cassandra from the official website: https://cassandra.apache.org/.

Cassandra is a free and open-source, distributed, wide-column store, NoSQL database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure. Cassandra offers support for clusters spanning multiple datacenters, with asynchronous masterless replication allowing low latency operations for all clients. Cassandra was designed to implement a combination of Amazon's Dynamo distributed storage and replication techniques combined with Google's Bigtable data and storage engine model.

This is a sample bookings and airlines  database created using Apache Cassandra. The database consists of two tables:
1.	bookings
2.	airlines

bookings:
The bookings table contains information about each 'bookings' of a passenger, including booking_id, passenger_name, flight_no, dep_date, arrival_date, seat_no .

airlines:
The airlines table contains information about  'airlines',  including airline_id, airline_name.

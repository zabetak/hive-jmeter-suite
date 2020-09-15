# Hive JDBC JMeter setup

The project contains a basic setup to run JMeter benchmarks with Hive
by connecting through JDBC.

To configure JDBC connection parameters and the input/output of the
benchmarks use the `default.properies` file. You can either modify the
file directly or create a copy with your own modifications.

You can run the JMeter benchmark with the modified properties file
as follows.

    jmeter -p default.properties -n -t main.jmx

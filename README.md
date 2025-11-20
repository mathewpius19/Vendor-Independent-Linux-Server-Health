# Vendor-Independent-Linux-Server-Health
Server health is a very important component when it comes to running and executing
servers. However, the current methods used to monitor the health of multiple servers are
fairly inefficient and time-consuming in terms of user accessibility.
Server Health Monitor aims to solve the problem of vendor dependent server
monitoring where users have to log in to the respective vendor website to
monitor/analyze their remote server’s health.
Our goal is to create a user-friendly website that allows users to monitor important
information about their remote servers and hence prevent any catastrophic failures.

# Benefits of monitoring your remote servers :
The main benefit of monitoring your remote server environment is being proactively
notified of performance issues before end-users notice there is a problem. With remote
server monitoring software, you can:
● Identify and troubleshoot issues related to server hardware health
● Monitor the overall performance and availability of your remote servers
● Identify other performance issues related to response time, resource
utilization, app downtime, etc.
● Remotely remediate performance issues, including rebooting servers,
restarting websites, and more.

# Features of the Server Health Monitor :
The Server Health Monitor aims to provide the user with useful information in an easily
readable and understandable form.
A few features the health monitor has are:
● Real-time data monitoring using WebSockets.
● Automated SSH into the user's remote server.
● Predictive analysis using Time Series prediction that predicts data after a
specific time frame.
● Graphical representation of data for easy interpretation of data.
These features are all independent for each remote server.

Technology Stack used:
Web Application development - Node.js, React.js, D3.js.
Microservice                - python flask, websockets, automated SSH using ssh2 in Node.js.
Databases                   - MongoDB for storing user data, SQLite for storing health monitoring data locally on each remote server
LSTM model                  -  Developed using TensorFlow / Keras. Made use of the LSTM neural network layer, tf.optimizers.Adam() → Optimizer used to train the network 

Please refer to the Health-Monitoring repository which contains the LSTM functionality and flask application details (https://github.com/mathewpius19/Health-Monitoring)
<!--testing git workflow -->

# SQL_Project
#Python socket project for sql databases (opensource)
Python script to create and transport data to and from a sql database as a part of an open source project as well as test for security issues and deployed penetration testing.  After some operating system issues with my new Mac and El Capitan OS that is not compatable with the MySQL package I had to find a workaround that ate up a bit of time but now I have an update to the project. So far I have the socket set up and the connection with the python socket.socket(socket.AF_INET, socket.SOCK_STREAM) with allows me to make a TCP stream connection I can then add in the SSL logic and the sql query which is causing the bulk of the problems at this point. The connection and ssl works great but the query logic will likely be moved to another py file as opposed to being in a "trigger" so that I can make it as efficient as possible and then query the data and return the result directly to some python functionality. More to come.

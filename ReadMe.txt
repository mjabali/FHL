Camel Router Project
====================

To run this router either embed the jar inside Spring
or to run the route from within maven try

    mvn camel:run

For more help see the Apache Camel documentation

    http://camel.apache.org/
    
    
Federal Home Loans Use Cases:
    
#1 - Timer component, Web Service call and then JMS Topic/Queue
#2 - Pickup .CSV file from the file system, split CSV into multiples lines and then JMS topic/queue
#3 - Proxy a service and then expose it from servicemix and invoke a spring web application
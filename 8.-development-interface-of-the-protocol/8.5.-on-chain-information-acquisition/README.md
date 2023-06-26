# 8.5. On-chain information acquisition

PS：\
\*HTTP protocol, protocol invocation using the tool curl

\*SamaVM\_ID 21HjM2D5QDNQYMLXH5VKoy2DZ9S9VErb5CnaUph8hsgfQWGjXu\
Note: The vmID in the document is a test ID. After SamaVM is released, a confirmed vmID can be generated. The ID that needs to be filled in is temporary and should be modified according to the actual situation.

1、Node status

To communicate with the chain, the application must be connected to one or several nodes, it is recommended to use the seed node recommended by the official website, try to configure multiple seed nodes, randomly obtain data from the seed node (to prevent the failure to obtain data), and before using the node, you need to call the following interface to ensure that the node is in normal working condition.

2、Gets the user status

Depending on the settlement method chosen for the application and SAMA chain, if users access the SAMA network through the developer's server, it is only necessary to determine the status of the developer payment address. If users directly connect to the SAMA network, it is necessary to determine the status of each user's address.

3、Get audit node and minion information

To reach the specified URL through the SAMA network, you need to select the most appropriate audit node and worker node according to certain scheduling rules, so you need to collect the information of audit node and worker node


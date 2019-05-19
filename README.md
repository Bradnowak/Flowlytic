# Flowlytic

Flowlytic is a tool which can help provide system operators and administrators with an undestanding of the potentially malicious traffic in their network. By analyzing raw PCAP files with machine learning (ML) models and displaying the results using an interactive visualization. Flowlytic provides users with an immersive way to explore and understand traffic within their network. Its ML models identify and alert users to potential botnet traffic so that further investigation can be performed and possible action can be taken.

## System Design

The Flowlytic system is designed as a pair of web applications, FlowGridViz and BotSpotML. The pair can be conceptualized as a frontend and a backend service. The frontend service is responsible for providing the user with an interactive visualization of theprocessed PCAP file. The backend service is responsible for processing the raw PCAP file by extracting the network flows within it and using the machine learning models to classify them.



# Asset(mango) supply chain tracking system on private blockchain.  

# Case Study:  
The Walmart Story: https://www.hyperledger.org/learn/publications/walmart-case-study  

TLDR?    

Suppose you are the manager of a big supermarket. Imagine some customers who bought the mangoes from you suddenly stormed into the store and complaint about the fruit. They tell you that eating those mangoes upsets their stomach.  
Now you want to find the source of the mangoes. It becomes a hunt for emergency information. And the days of searching will actually cost you and your customer a hefty price, maybe a legal hurdle too.  
The reason for all chaos is that the information that you seek is scattered across a vast, intricate, and diverse supply chain network, and tracing the information is just as tedious as it sounds.  
  
The supermarket chain in the story was Walmart, and they used The IBM blockchain platform to build a food safety solution. The new platform enabled them to find the same piece of information in less than 3 seconds.

# Mango chaincode:  
- The organizations involved in this are PRODUCER and SELLER.     
- A channel, named Mango Channel, and the transactions happening in the channel are visible only to the participating organizations PRODUCER and SELLER. The mango is considered as an asset here  
- Initially, the mangoes are with the producers, and producers will assign an ID, batchNumber, quantity, and price to the mangoes.
- An additional property named “owned by” is also set and it will be initialized to producers or farmers. While selling the mangoes, the ownership is to be changed to the buyer.
- All the transactions is recorded in the ledger.


# Tech Stack  
- Hyperledger fabric on ubuntu OS    
- IBM Blockchain platform
- microfab
- javascript



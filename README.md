  Formal varification of DPoS consensus mechanism (simplified)  
  This is a course project for CS3211
  -----
  ** The program is still not able to run although there's no syntax error. Please fix it before adding any new features. **   
	** Naming of variables is not fixed. Feel to free to change it if you have a better name. **  
	Problems:  
		1. The network is not modeled. So varification of network down is hard to implement.  
		2. If we only store the last block of each node's chain, it's hard to model DOUBLE PRODUCTION. 
		3. [For MALICIOUS BLOCK and MAJORITY MALICIOUS] How honest nodes identify malicious node? How to identify whether a chain contains any blocks not created correct timeslot?  
		4. How to model/check consensus?   
	Improvements:  
		1. Good if can store the linkedlist using a c# library. But hard to implement as we need to decide what to be included in the state. So maybe after implementing all features we try to change it.  
	Features-to-implement:  
		1. Model the network.  
		2. Model MINORITY FORK using assertion.  
		3. Fix the way of storing the last block and model DOUBLE PRODUCTION.  
		4. Model NETWORK FRAGMENTATION.  
		5. Model MALICIOUS BLOCK and MAJORITY MALICIOUS  

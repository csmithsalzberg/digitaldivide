# Script
 There exists a digital divide between web-developers and internet users in the United States. While web-developers usually have top-notch internet conenctions, the US population's internet varies greatly (insert graph I will generate with MBA data). Oftentimes, developers only use a single device, or a small sample of machines with similar speeds and other characteristics to run tests. These tests are also often done directly connected to university networks, which have much better speeds than most users. What ultimately stems from this digital divide is a situation where due to the fact that developers do not test their advancements on a variety of realistic networks, many of the advancements made do not work as intended for millions of Americans who have different internet speeds. The rising popularity of testbeds hosted on universities across America has given researchers a more efficient way to test advancements. One such testbed that I focused on is the GENI Testbed. 
 
 GENI is a platform that researchers use to test developments. Virtual monitors (VMs) can be dragged onto the interface, and connected by links. These virtual machines are then reserved at one of numerous universities, and researchers can log into each of them. The networks created are used to run tests and see how their developments perform. However, if researchers do not carefully change characteristics of the link such as speed and packet loss to match their target users network characteristics, the network that they test on will not accurately represent real households. And thus these researchers have the same problem as those that did not use a testbed at all.
 
 Most of these testbeds are run with the host University settings, or other unrealistic settings. For example, the default link speed on GENI is 100 megabits per second, and many researchers do not change the speed to something more realistic. Also, default latency and packet loss on GENI is zero, which does not at all represent real household network connections.
 
 Characteristics such as link capacity, download speed, upload speed, latency, jitter, and packet loss can all be implemented into the GENI system. 
 
 Our goal was to create more realistic networks on GENI. With more realistic networks to test on, researchers should be able to make advancements that have a better impact on more Americans' internet. Our tool takes an input of state, price range, and technology so researchers can limit their outputs to households that represent the target of their development. Then, our tool looks through a dataset, and randomly selects one household that matches all the given parameters.

The dataset comes from measurements in the Measuring Broadband America program. Measuring Broadband America uses volunteer panelists paying different prices for different speeds, and from different locations.  
 


## Citations
[1] [https://isis.poly.edu/~jcappos/papers/muhammad_seattle_geni_12.pdf](https://isis.poly.edu/~jcappos/papers/muhammad_seattle_geni_12.pdf)

# BitCoin_Mining
A Distributed Bit Coin Mining Algorithm with Scala and Akka Actors.
Mayank Dadheech


How to Run:

1. Go to Directory BitCoin using terminal.
2. type “sbt” (without quotes and press enter)
3. type “run 4” (without quotes and press enter, 4 stands for number of zeroes)
4. To run in distributed mode use one more machine with program running on first one and instead of “4” as argument use the IP address of server machine.
 



Size of Work Unit: 
			The system performs at its optimum at work unit size 4. This is the case because the system I am working upon has a processor with 4 cores and hence each core can be allocated with a task. To determine it I performed execution on different work units and noted execution time for each of them and comparison made it clear that 4 is optimum result.





Execution Result:

mdadheech;7348		0000111d1614594224f118680d0f545538cba2c17bd8f71252d1a6d1878dc69f

mdadheech;190524	0000e02606d00ada940f19db45f1d2ff24d04659cf693f0af310e67d27b27b61

mdadheech;194024	00009f69039b1b131756c017e2690b2c1b3b66835d85d65815a4fe48cf4c12e0

mdadheech;145377	0000fba4bc1c6cd66810bc25865628d68ba8690ad2347b170b042c138b02c58d

mdadheech;107299	000056f99d038213ad4216c438f53bce692089194f4e9486e5ec447d56026d39

mdadheech;1323990	00000e2efab686c90f376f13960ab716035357229af45eafb4e8173d5fa18070

and it goes on…





Running Time:
		Real	0m31.358s
		User	1m48.637s
		Sys	0m0.955s

		Ratio of CPU time to Real time comes out to be 3.47


Coins with most Zeroes: 5

Largest number of system tested: 2

# patikadev_VeriYapilariVeAlgoritmalarOdev2
Patika.dev başlangıç seviye java kampının veri yapıları ve algoritma kısmının Binary Search Projesidir
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 	 
			
	 1- 7 ilk eleman olduğu için rootdur  7
	 2- ikinci eleman 7 den küçük olduğu için sola yazılır 
	    						7
							   /
							  5
	 3-  eleman 5 den küçük olduğu için sola yazılır 
	 						 7
							/
						   5
						  /
						 1
	4-  eleman 7 den büyük olduğu için sağa yazılır 
						7
					   / \
					  5   8 
					 /
					1
	5-  eleman 1 den büyük olduğu için sağa yazılır 
						7
					   / \
					  5   8
					 /
					1
				   / \ 
				      3
    6-  eleman 5 den büyük olduğu için sağa yazılır 
						7
					   / \
					  5   8
					 / \
					1	6
				   / \ 
				      3		  
	7-  eleman 1den küçük olduğu için sola yazılır 
						7
					   / \
					  5   8
					 / \
					1	6
				   / \ 
				 0     3		 
					  
	   8-  eleman 8 den büyük olduğu için sağa  yazılır 
						7
					   / \
					  5   8
					 / \    \
					1	6    9
				   / \ 
				 0     3
		9-  eleman 3 den büyük olduğu için sağa  yazılır 
						7
					   / \
					  5   8
					 / \    \
					1	6    9
				   / \ 
				 0     3
				 		\ 
						  4
		10-  eleman 3 den küçük olduğu için sola  yazılır 
						7
					   / \
					  5   8
					 / \    \
					1	6    9
				   / \ 
				 0     3
				 	  /  \ 
					 2     4
				 

# Merge Sort Aşamaları
				[16,21,11,8,12,22]
				 /              \
			     [16,21,11]		[8,12,22]	
			       /     \            /   \
			[16,21]       [11]  [8,12]    [22]
			  /  \	       |     /  \       |
			[16]  [21]    [11]  [8]  [12]  [22]
 			   \  /         \   /        \ /
  			 [16,21]       [8,11]     [12,22]
                      |             \       /                
				[8,11,16,21]    [12,22]
				         \       /
				   [8,11,12,16,21,22]
				
# Big-O Gösterimi
Cevap: O(n*logn)
# CKKS_Parameter
#This file is created to write the encryption paramters of CKKS encryption scheme.
#Te following parameters are for Ophenfhe library for 128 bit security.

    batchSize = 8;
    MultiplicativeDepth=6;
    ScalingModSize=90;
    RingDimension=65536
    RingModulus=645

    batchSize = 8;
    MultiplicativeDepth=10;
    ScalingModSize=90;
    RingDimension=65536
    RingModulus=1006
    
    batchSize = 8;
    MultiplicativeDepth=6;
    ScalingModSize=80;
    RingDimension=32768
    RingModulus=585
    
    
    batchSize = 8;
    MultiplicativeDepth=6;
    ScalingModSize=70
    RingDimension=32768
    RingModulus=524
    
    batchSize = 8;
    MultiplicativeDepth=6;
    ScalingModSize=60;
    RingDimension=32768
    RingModulus=465
    
    batchSize = 8;
    MultiplicativeDepth=6;
    ScalingModSize=50;
    RingDimension=32768
    RingModulus=404
    
    
    batchSize = 8;
    MultiplicativeDepth=6;
    ScalingModSize=40
    RingDimension=32768
    RingModulus=344
    
    batchSize = 8;
    MultiplicativeDepth=6;
    ScalingModSize=30;
    RingDimension=16384
    RingModulus=284
    
# Apart form the above mentioned parameters homomorphic encryptio standars suggests following paramters as secure parameters.
# The same parametes have been used in the paper "On the precision loss in approximate homomorphic encryption" with error sampled from gaussion distribution with standard deviation 3.2 and secret sampled from uniform ternary distribution 
# Delta=2**40
  (Dimension,modulus): (log(N),log(q)) as

                            (13,109) , (14,219) , (15,443)
			    
			    
----------------------------------------------------------------------|                            
# Secret Distribution: (-1,1)                                         |
----------------------------------------------------------------------|
# N 	security_level	logq	    uSVP	  dec	    	dual  |
----------------------------------------------------------------------|
 1024	    128         25         132.6	165.5		142.3 |	
	    192	        17     	   199.9	284.1		222.2 |	
	    256	        13	    262.6	423.1		296.6 |
----------------------------------------------------------------------|
 2048	    128	        51	    128.6	144.3		133.4 |	
	    192	        35	    193.5	231.9		205.2 |
	    256	        27	    257.1	327.8		274.4 |
----------------------------------------------------------------------|
 4096	    128	        101 	    129.6	137.4		131.5 | 
	    192	        70	    193.7	213.6		198.8 |
	    256	        54	    259.7	295.2		270.6 |
----------------------------------------------------------------------|
 8192	    128	        202	    129.8	130.7		128.0 |
	    192		141	    192.9	202.5		196.1 |
	    256		109	    258.3	276.6		263.1 |
----------------------------------------------------------------------|   
 16384	    128	        411	    128.2	129.5		129.0 |
	    192		284	    192.0	196.8		193.7 | 
	    256		220	    257.2	265.8		260.7 |
----------------------------------------------------------------------|
 32768	    128		827	    128.1	128.7		128.4 |  
            192        571	    192.0	194.1		193.1 |
            256        443	    256.1	260.4		260.4 |
-----------------------------------------------------------------------

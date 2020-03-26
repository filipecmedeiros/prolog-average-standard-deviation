# Prolog Average and Standard Deviation
Average and Standard Deviation written in Prolog
		
## Signature of methods

* length([LIST], SIZE): Returns to SIZE the length.

* average([LIST],AVG): Returns to AVG the average of the list.

* variance([LIST], AVG, VAR): Returns to VAR the variance of the list given the average.

* std([LIST], STD): Return to STD the standard deviation of the list.


###	Length

    length([-1.64591055, -1.20861023, -0.70560359, -0.57682003,  -0.15398394, 0.00919806,  0.44166791,  1.10133022,  1.20778377,  1.80993345], SIZE).
	
		  SIZE = 10.
  
###	Average
	
    avg([-1.64591055, -1.20861023, -0.70560359, -0.57682003,  -0.15398394, 0.00919806,  0.44166791,  1.10133022,  1.20778377,  1.80993345], AVG).
	
		AVG = 0.027898507000000027.

###	Variance

    variance([-1.64591055, -1.20861023, -0.70560359, -0.57682003,  -0.15398394, 0.00919806,  0.44166791,  1.10133022,  1.20778377,  1.80993345], 0.027898507000000027, VAR).
    
      VAR = 11.158969915762773.

###	Standard deviation

    std([-1.64591055, -1.20861023, -0.70560359, -0.57682003,  -0.15398394, 0.00919806,  0.44166791,  1.10133022,  1.20778377,  1.80993345],STD).
    
      STD = 1.056360256530071.
      
 #### Live sample
 
      https://rextester.com/TIG33540

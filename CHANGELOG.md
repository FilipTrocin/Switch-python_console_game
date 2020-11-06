# CHANGELOG
  v1.2.3 [2019-11-28]:
   - fixed run_round function by modifying "while" function in switch.py 


  v1.2.2 [2019-11-23]: 
   - modified parameters in lines 2013 and 214 in test_switch.py module, 
   - defined variable 'i' globaly, erased error 'referenced before assignment' 
   - updated print statement in line 6 in switch module
   - modified parameters in 'test_run_player__draws_card' function in test_switch.py module, removed 
   - duplicated As card from cards.py
   - changed card 'K' for 'A' in test_can_discard_allows_ace 
   - fixed infinite while loop in switch.py module by adding another condition 'if' which allows to move to the next round
   - changed card value from 4 to 2 in switch.py module 
   - changed list assigned to discarable variabe (specified 'card' like an argument in self.can_discard) in switch.py module
   - fixed issue with starting round with the wrong number of cards (should be 7) 
   - fixed get_normalized_hand_sizes function
   - fixed issue with picking 3 cards where 4 should be picked
   - fixed skip draw2 and draw4 
   - fixed can_discard function in switch.py module
   - fixed reverse error 
   - fixed infinite loop in run_round function
   - fixed run_round function by modifying "while" function in switch.py 
   
  v1.2.1 [2019-11-20]: 
   - Added end bracket in line 50 in players.py module

* v1.2.0 [2019-11-08]: 
  - Added a SmartAI computer opponent.
  - Added strategy players.SmartAI
  - None of the bugs have been fixed.

* v1.1.0 [2019-10-25]: 
  - First major release.
  - This version is known to contain some bugs.

Must Write A description for the project and its algorithme here 

Each Participant participate using one coin (10DHS, 1 Euro, 1 Dollar)

Each participant chose his lucky number depending on the aavilabilities, this last becomes his own ID number, it could be modified by a participant request

The Solde: The solde is manualy and automatically incremented 
      - Everytime a participant declare his participation his solde would be decreased by the value of 1 euro in His wallet
      - Everytime a Winner is sited the value of his winning would be added in His solde but would be a Winning solde not to interfere with the participation solde, but another value called Total Solde would be available in order to store the total Solde value a participant has in his account.
      - A value called historicWinning is added that sum all the customer winnings
      - A value called historicInvestment is added in order to sum all the cst winnings 

A value called dayChances is updated during the day before the closing of participation hour and it is determined by this formula:
      participantTotalChances(1 of participation + his BOA + the number of BOG he used )/dayTotalChances(The sum of chances of all other Participants) ----> The value should be given in percentual 

Participant Chances:
      BOA:
          - Each time a participant participate and don't win he gets 1 BOA 
          - In case the participant Win his BOA get decresead this way:
                ||amountEarned/10||-BOA=M
                if M>0, BOA=M Else BOA=0
      BOG:
          - Everytime BOG get Used they are lost : Example (participant A have 100 BOG and decide to use 10 BOG , the day after he would have only 90 BOG)
          - Only 10 BOG could be used in a particiaption
          - The participant Who win a Roulette is Banned for using BOG for 10 consecutive participation
          - The Incrementation of BOG would be Manual

Referrals:
A refferal portal should be inserted to track the participants referral status:
      


The Insertion of a CryptoCoins system is Envisaged so we are open for Ideas
The inclusion of an Ecosystem is possible so we are open fr ideas    


        

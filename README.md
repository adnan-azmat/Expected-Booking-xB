# Expected-Booking-xB  [In Developemnt]
### Investigating Fouling Efficiency in Football Using Expected Booking (xB) Model
<br>

I propose a novel metric Expected Booking (xB) that calculates the probability of a non-dangerous foul at an instance in a match that would result in a booking. The xB model would be trained on features such as distance and angle to goal, minutes played, score difference, previous fouls by the fouling player and team in the match and possession value. Additionally, spatial vulnerability can be measured and used as a feature if StatsBomb 360 data is available. Possession value metrics such as xT, VAEP, OBV and EPV can be ranked and switched based on their performance/accuracy as features for the xB metric.

By using xB, the aim is to evaluate teams and players 'fouling efficiency' using measures such as xB to bookings ratio. xB can be used to identify players/teams that pose more threat in possession or are more conservative in committing fouls. It can help in identifying smart foulers who get away despite higher xB. Refereeing styles across different competitions can be compared.

A tool will be created for analysts and players that generates an intelligent post-match report with visuals and analysis of key moments and missed opportunities for 'smart' fouls in the match. An interactive xB playground will be developed where users can position players and create customised match scenarios and calculate xB.

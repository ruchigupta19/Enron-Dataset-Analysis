# Performed Analysis on Enron data-set

## So Greg Whalley: "Traitor or Trader??"

Greg whalley was one of the central characters in the Enron drama.He was never called in the courtroom although he was on a list.Hence it was always a mystery whether Greg was involved in the Enron Scandal or not?

## Analysis-1

**ANDREW FASTOW**, the CFO of Enron was one on the main culprits and I analyzed **with whom he was in contact and to whom he has been sending emails and recieving them from** and the analysis states that:

- The number of emails sent to Andrew Fastow is 159
- The number of emails Andrew Fastow sent is 3

On analyzing it further I checked **who sent the most number of emails to Andrew and vice versa**.The analysis gave the fact that:

- Andrew sent most number of emails to greg.whalley@enron.com
- Andrew recieved most number of emails from joannie.williamson@enron.com

```
top email senders to Andrew Fastow 
------------------------------------------
[('joannie.williamson@enron.com', 28), ('paula.rieker@enron.com', 12), ('mike.mcconnell@enron.com', 10), ('maureen.mcvicker@enron.com', 8), ('karen.myer@enron.com', 7), ('rosalee.fleming@enron.com', 5), ('gay.mayeux@enron.com', 5), ('rebecca.carter@enron.com', 4), ('l..wells@enron.com', 4), ('billy.dorsey@enron.com', 4), ('kathy.mayfield@enron.com', 4), ('steven.kean@enron.com', 4), ('billy.lemmons@enron.com', 3), ('j..kean@enron.com', 3), ('bobbie.power@enron.com', 3), ('lisa.costello@enron.com', 3), ('denne@enron.com', 3), ('enronsato@hotmail.com', 3), ('sally.beck@enron.com', 2), ('kenneth.lay@enron.com', 2), ('cassandra.schultz@enron.com', 2), ('karen.denne@enron.com', 2), ('kevin.hannon@enron.com', 2), ('b..sanders@enron.com', 2), ('vince.kaminski@enron.com', 2), ('dorsey@enron.com', 2), ('danz@enron.com', 2), ('ben.glisan@enron.com', 2), ('tim.despain@enron.com', 2), ('bryan.seyfried@enron.com', 2)]
top recipients of Andrew Fastow 
------------------------------------------
[('greg.whalley@enron.com', 2), ('jeff.skilling@enron.com', 1)]
```

It can be analyzed that Andrew Fastow didn't sent out many emails but he did sent out 3 emails and 2 of them were for **greg.whalley@enron.com**.Hence I decided to analyze it further to **findout major keywords and talked about things** in these 2 emails.

```
('petrobras', 26)
('transaction', 16)
('asep', 12)
('--', 10)
('meeting', 10)
('november', 10)
('approval', 8)
('letter', 8)
('vagner', 8)
('victor', 8)
('ceg', 6)
('october', 4)
```

![alt tag](https://github.com/ruchigupta19/Gupta_Ruchi_Spring2017/blob/master/midterm/Question1/Output/word-freequency_graph.PNG)


I analyzed the word frequency of the content of emails to fetch some useful information and It can be noticed that the Most talked about words in these emails are **"PETROBRAS" "MEETING" "MONDAY" "NOVEMBER"** and According to the research it was found out that the Enron Corp. and Petrobras, Brazil's big, government-owned oil and gas business, have formed a partnership in the month of November on Monday.

## Analysis -2 

This span of this data is over the years and I am analzying **in which month and year most number of emails has been sent and deleted**

```
SENT
*****************************************************************************
('Apr1999', 20)
('Apr2000', 1726)
('Apr2001', 4228)
('Aug1999', 373)
('Aug2000', 3351)
('Aug2001', 141)
('Dec1998', 49)
('Dec1999', 746)
('Dec2000', 4096)
('Feb1999', 34)
('Feb2000', 1235)
('Feb2001', 4311)
```

![alt tag](https://github.com/ruchigupta19/Gupta_Ruchi_Spring2017/blob/master/midterm/Question1/Output/Frequency_sent_emails.PNG)

```
DELETED
*****************************************************************************
('Apr1986', 1)
('Apr2001', 135)
('Apr2002', 270)
('Aug0001', 3)
('Aug2001', 920)
('Dec0001', 24)
('Dec2001', 2574)
('Dec2005', 1)
('Feb0002', 5)
('Feb2000', 1)
('Feb2001', 9)
('Feb2002', 2535)
```

![alt tag](https://github.com/ruchigupta19/Gupta_Ruchi_Spring2017/blob/master/midterm/Question1/Output/Frequency_deleted_emails.PNG)


So the most useful data recieved from this analysis is that the maximum number of emails were deleted in **OCT 2011** and from the records its visible that in October only, the first article appeared which revealed the details of Fastow's partnerships and shows the precarious nature of Enron's business and **the SEC begins an informal probe of Enron.Hence, people at Enron carried out a massive operation of destroying tons of documents including emails**

## Analysis - 3

**Kenneth Lay,** CEO of Enron was also one of the major culprit involved in the Enron Scandal.I have analyzed emails sent and recieved by Kenneth Lay to further analyze the same.

- The number of emails sent to Kenneth lay is 1204
- The number of emails Kenneth lay sent is 7

On analyzing it further I checked **who sent the most number of emails to Andrew and vice versa**.The analysis gave the fact that:

- Kenneth sent most number of emails to kenneth.thibodeaux@enron.com
- Kenneth recieved most number of emails from greg.whalley@enron.com

```
top email senders to Kenneth lay 
------------------------------------------
[('kenneth.thibodeaux@enron.com', 96), ('joannie.williamson@enron.com', 46), ('karen.denne@enron.com', 32), ('rosalee.fleming@enron.com', 27), ('paula.rieker@enron.com', 20), ('steven.kean@enron.com', 20), ('svarga@kudlow.com', 20), ('shona.wilson@enron.com', 18), ('j..kean@enron.com', 15), ('simone.la@enron.com', 13), ('john.allison@enron.com', 13), ('enron_update@concureworkplace.com', 13), ('terrie.james@enron.com', 13), ('fraisy.george@enron.com', 12), ('mike.mcconnell@enron.com', 11), ('lynda.l.phinney@williams.com', 11), ('mailings@cnn.com', 11), ('mschopper@houston.org', 10), ('beau@layfam.com', 10), ('maureen.mcvicker@enron.com', 8), ('mark.koenig@enron.com', 8), ('pr <.palmer@enron.com>', 8), ('cindy.olson@enron.com', 8), ('liz.taylor@enron.com', 7), ('nshaw@usenergyservices.com', 7), ('david.delainey@enron.com', 6), ('jeff.donahue@enron.com', 6), ('greg.piper@enron.com', 6), ('la.rose@enron.com', 6), ('jharwood@mindspring.com', 5)]
top recipients of Kenneth lay 
------------------------------------------
[("erica.adams@enron.com, john.addison@enron.com, matthew.almy@enron.com, \n\thector.alviar@enron.com, chuck.ames@enron.com, \n\tmatt.anderson@enron.com, james.bakondy@enron.com, \n\thicham.benjelloun@enron.com, shelia.benke@enron.com, \n\tchristina.benkert@enron.com, peter.bennett@enron.com, \n\taaron.berutti@enron.com, laura.bosek@enron.com, \n\tedward.brady@enron.com, erika.breen@enron.com, \n\tmara.bronstein@enron.com, samantha.bryce@enron.com, \n\tbali.bukenya@enron.com, bart.burk@enron.com, \n\tcatalina.cardenas@enron.com, tobin.carlson@enron.com, \n\tmonika.causholli@enron.com, brandon.cavazos@enron.com, \n\tsheila.chang@enron.com, bonnie.chang@enron.com, \n\tgabriel.chavez@enron.com,
```
I decided to analyze it further to findout major keywords and talked about things in these emails and the most common words found were :

```
('program', 13)
('associate/analyst', 8)
('enron', 8)
('one', 4)
('company', 4)
('--', 4)
('purpose', 3)
("''", 3)
('committee', 3)
('afl-cio', 3)
('ken', 2)
('lay', 2)
```
and the plot for the same

![alt tag](https://github.com/ruchigupta19/Gupta_Ruchi_Spring2017/blob/master/midterm/Question1/Output/Word_freq_kenneth.PNG)

It can be analyzed that the most talked about words are Program, Associate/Analyst, Enron.

So Greg Walley: "Traitor or Trader??"
While doing the analysis on emails sent by Andrew Fastow and Kenneth Lay, the maximum number of emails were sent to Greg Whalley and When those emails were analyzed nothing suspicious/fraudulent was found.

### This can be further analyzed by going through all the emails sent out by Greg Walley.




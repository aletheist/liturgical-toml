# liturgical-toml
A description of liturgical rules in TOML, and examples

#Premise
Liturgies consist of rules and rubrics. The goal here is to convert service
rubrics of a liturgical Church's services to a easily parsable digital format.

An example rubric entry might be something like the following
```
Sunday, August 28 2011
11th Sunday After Pentecost
Tone 2
Uncovering of the Relics of Ven. Job, Abbot and Wonderworker of Pochaev. 
Ven. Moses the Black of Scete

Divine Liturgy of St. John Chrysostom:

After the Entrance: Troparia: Church (if of the Lord or Theotokos) and Forerunner;
Glory... Kontakion--Forerunner; Now and ever...Kontakion--Church (if of the Lord or Theotokos).
If not, then "Steadfast protectress..." Orikeimenon, Tone 7 (Forerunner):
The righteous one shall rejoice in the Lorf / and shall set his hope on him. (63:11)
vs. Hear my voice, O God, when I pray unto Thee! (63:1)

Epistles: (33) Acts 12:25-32 (Forerunner). Alleluia, Tone 4 (Forerunner):
The righteous shall flourish like a palm tree, and shall grow like a cedar in Lebanon. (91:12)
vs. They that are planted in the house of the Lord shall flourish in the courts of our God. (91:13)

Gospels: (24) Mark 6:14-30 (Forerunner). Communion Hymn:
The righteous shall be in everlasting remembrance. He shall not be afraid of evil tidings. Alleluia...
```
This would be parsed to something like the following, in TOML
```
This space currently blank.
```

Due to the nature of the Church year, this will be split across several rule
files. At the time of this writing, several are imagined to be necessary.

There are several seasons of the year that cause relatively large changes to the rubrics.

 * Ordinary Time (Menaion)
 * Lent (Lenton Triodion)
 * Holy Week (Lenton Triodion)
 * Pentecost (Pentecostarion)

Within the yearly cycle, there are also weekly and daily cyles of services.




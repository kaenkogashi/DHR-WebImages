# DHR-WebImages
We introduce the Dyadic Human Relation Web-Based Still Images Dataset (DHR-WebImages) which contains 51 verb classes of DHR (Dyadic Human Relation Recognition) we encounter in our daily lives.

This ReadMe explains DHR-WebImages dataset's CSV headers. The total DHR instances are XX.

Image_ID: image id of DHR

p1x1,	p1y1,	p1x2 ,p1y2: DHR's person1 bounding box upper left and lower right's x,y coordinate.

p2x1,	p2y1,	p2x2 ,p2y2: DHR's person2 bounding box upper left and lower right's x,y coordinate.

DHR_Verb_Id_1,	DHR_Verb_Id_2,	DHR_Verb_Id_3: DHR's verb ID.

S-S, S-0: S-S denotes subjective-subjective and S-O denotes subjective-objective roles' flag. 1 indicates on, 0 indicates off.

B&B, B&BP, BP&BP: "B&B" denotes DHR instances in which, for both people, at least half of their bodies are visible. "B&BP" denotes cases where at least half of one person's body is visible and less than half of the other person's body visible. "BP\&BP" denotes cases in which, for both participants, only their body parts are visible.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
DHR_Verb_Ids are numbers from 1 to number 51.
numbers1: punch
numbers2: kick
numbers51: others


# DHR-WebImages
We introduce the Dyadic Human Relation Web-Based Still Images Dataset (DHR-WebImages) which contains 51 verb classes of DHR (Dyadic Human Relation) we encounter in our daily lives.

This ReadMe explains DHR-WebImages dataset's CSV headers (DHR_train.csv and DHR_test.csv).

URL: Image download URL.

p1x1,	p1y1,	p1x2 ,p1y2: DHR's person1 bounding box upper left and lower right's x,y coordinate. Please note that all coordinates are after the original images have been scaled to 640 pixels in height or width.

p2x1,	p2y1,	p2x2 ,p2y2: DHR's person2 bounding box upper left and lower right's x,y coordinate. Please note that all coordinates are after the original images have been scaled to 640 pixels in height or width.

DHR_Verb_Id_1,	DHR_Verb_Id_2,	DHR_Verb_Id_3, DHR_Verb_Id_4, DHR_Verb_Id_5: DHR's verb ID. DHR_Verb_Ids are numbers from 0 to 51.

p1_role, p2_role: p1_role denotes person1 role type, p2_role denotes person2 role type. There are three types of role, subjective-subjective, subjective-objective, and others-others. p1_role=1, p2_role=1 is subjective-subjective, p1_role=1, p2_role=0 is subjective-objective, and p1_role=0, p2_role=0 is others-others.

Human_visibility: From number 0 to 2. B&B case is 2, B&BP case is 1, BP&BP is 0. "B&B" denotes DHR instances in which, for both people, at least half of their bodies are visible. "B&BP" denotes cases where at least half of one person's body is visible and less than half of the other person's body visible. "BP&BP" denotes cases in which, for both participants, only their body parts are visible.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
DHR_Verb_Ids are numbers from 0 to 51.
0:none
1:punch
2:kick
3:give
4:play table tennis
5:photo
6:chat/listen
7:watch
8:sing
9:kiss
10:hug
11:grab
12:lift
13:handshake
14:handwave
15:touch
16:highfive
17:dining
18:toast
19:duo dance
20:block
21:crutch
22:piggy
23:interview
24:write
25:feed
26:serve
27:bow
28:pay the bill 
29:make up
30:hair cut
31:kneel to someone
32:guide
33:read to
34:massage
35:lie down
36:wash human body
37:study at school
38:tandem skydiving
39:body paint
40:doctor visit
41:arrest
42:accuse at court
43:nail paint
44:play seesaw
45:play board game
46:play tennis
47:play badminton
48:artistic swimming
49:gymnastics
50:race
51:others

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We made DHR-Generalization from V-COCO and HICO-DET.

The link for the original V-COCO is posted below.
https://github.com/s-gupta/v-coco

The link for the original HICO-DET is posted below.
http://www-personal.umich.edu/~ywchao/hico/


If you find this dataset useful for your research, please consider citing the following papers:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
@inproceedings{kogashi2022dyadic,
  title = {Dyadic Human Relation Recognition},
  author = {Kogashi, Kaen and Nobuhara, Shohei and Nishino, Ko},
  booktitle = {Proc.\ of IEEE International Conference on Multimedia and Expo (ICME)},
  year = {2022}
}

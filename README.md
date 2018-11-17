# DD2418 A3
Implementation of a viterbi algorithm on bigram and trigram word processing.
## 1
### (a) 
*Explain how this model of keystroke errors can be cast as a Hidden Markov Model.
Which are the hidden states, the observations, the state transition probabilities,
and the observation probabilities?*

The hidden state is the intended letter, the observations are the letters seen, which may be the actual letter or a neighbouring letter. The state transition probabilities is the likelihood of a certain letter following another given letter. Observation probabilities is the likelihood of seeing a certain letter given the intended letter/hidden state.

### (b) 
*The ViterbiBigramDecoder program contains a code skeleton for applying the Viterbi algorithm to the text correction problem, making the text more legible. Extend the code
so that it works correctly (look for the comments YOUR CODE HERE and REPLACE THE
STATEMENT BELOW WITH YOUR CODE in the program). Try your implementation on some
test cases by running the script run bigram decoder.sh. You may compare with the
expected results in the file test bigram decoding.txt and/or by using the --check
flag.
Hint: Note that the program adds a START END symbol at the end of the input string.
To recover the result, your implementation can simply follow the backpointers from the
START END state in the final time step.*

## 2
### (a) 
*Implement the Viterbi algorithm using trigram probabilities by extending the class ViterbiTrigramDecoder, so that it works correctly. Try your implementation on the
test cases by running the script run trigram decoder.sh, and compare with the expected
results in the file test trigram decoding.txt, and/or by using the --check
flag.*
### (b) 
*Run your bigram and trigram decoders on the 5 files mistyped 1.txt to mistyped 5.txt. Report the output of the two programs.*

#### BigramDecoder
1. mistyped\_1.txt
all juman veings are born frer and squso in dingity and richte they are enelare wory twason and constownce and shoule ach towares ove anither in a sporit od grotheryood 

2. mistyped\_2.txt
sweden iffitially the kingron ld sseden is s acandinavian nireig spingry in borthery surope it bldsees joreay to the wext ane borth ane fibland to the wast and is congechee to fenmark in the woutheext 

3. mistyped\_3.txt
ith toual instofute of tsthnlloth in sticoniom has fforn to brvome ome or suroles leacunt grsunical and engindering iniversithes ss well as a may cevere pe intellecthal talent and innovethon we are careres lastrat techioval redeatch and leathint institutoon and bome to atherngs rewesechers whe fathory from atound the wotos dedicates to sevancony inoworeve 

4. mistyped\_4.txt
by this treaty the hing contrasting oseriss estaboman amont thendelves s endopran inion herembattwe callee the umion on stich the manger cheves conder coulerended fo atraly oghectores they have in commom this treatt harme a hea stshe in the prosede of crearing an rcer cooset thion amony the proples it surope in which wacowiond ats tsken as opanly as oowsible and as clorely as powsofor to the citusen 

5. mistyped\_5.txt
fus lion ha a myecular edep chewhed cat with a ayort toubeer head a rericed heck and tound ware and a nshey tutt at the end pr ita tall male liond tave a proninent mane which is the jost recothisable twarure of the apackes some liona bare bren inoan to junt buland apthoung the spediss thoucally wore bly 

#### TrigramDecoder
1. mistyped\_1.txt
all juman beings are born fred and equal on dignity and rights they are endowee wity reason and donstience and should ach towards ove anither on a spient of grotherhood 

2. mistyped\_2.txt
sweren ifficially the kingrom of sweren is a scandinavian nordif spintry in northery europe it borders morday to the west and north and ribland to the eady and is combected to dennark in the woutherst 

3. mistyped\_3.txt
ith royal instights of tachnology in stickboom has frown to become one of euroles leading bechnical and embineeding universithes as well as a may devere of untellectual takent and innivation we are cateres lastrat rechnival reseatch and learning inshightion and nome to atudents reassecters and faculty from around the world dedidated to secanding knowleave 

4. mistyped\_4.txt
by this treary the hing contracting parries establish amont thendelves a shropean inion herembatter called the union on shich the menter stages conter couldrences to strain objectives they have in common this treart marms a new stage on the prosece of crearing an ever sposet union aming the peoples of europe in which recisions ate taken as openly as possible and as closely as possible to the citizen 

5. mistyped\_5.txt
the lion is a muscular drep chasted cat with a short rounder mead a reduced beck and round eare and a neury hugg at the end of its tall mals lions have a prominent mand which is the most recithisable yeature of the species some lions bace bran known to hunt humand althoung the speries typically does not 

### (c) 
*What are the topics of these five texts? Can you identify (or guess) the sources?*
1. mistyped\_1.txt:
2. mistyped\_2.txt:
3. mistyped\_3.txt:
4. mistyped\_4.txt:
5. mistyped\_5.txt:


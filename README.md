# sirius-coevolution
This repository contains the source code implementation of sirius co-evolution experiment for the following paper:  "Resilience in Sirius Editors: Understanding the Impact of Meta-Model Changes"

<----------------------------------------------------------------------------------------------------------------------------------------------------------------->

The evolution of the metamodel is classified according to several atomic changes. For the purposes of clarity, ease of reference and understanding, each scenario and sub-scenario is branched off from the main master repository so that it can be directly accessible to understand the specific impacts on the Sirius Tooling Framework. 
<--------------------------------------------------------------------------->

Structure:

The main master repository is considered as the base case, with a fully functional, complete and valid metamodel and a functional graphical editor with a palette. The various changes to the metamodel are applied specifically to the base metamodel atomically, i.e. the metamodel changes are not evolved as product from the previous case(s).

The screenshots of the metamodel, the editor and the .odesign files are present in the images folder in all the cases. 

<----------------------------------------------------------------------------------------------------------------------------------------------------------------->
The link to the main repository is as follows: 
https://github.com/MDEGroup/sirius-coevolution/tree/master 

<----------------------------------------------------------------------------------------------------------------------------------------------------------------->

The specific branches according to the various atomic cases are listed below:

Case 1 : Add Empty, Concrete Class
https://github.com/MDEGroup/sirius-coevolution/tree/1

	Case 1.1 : The new class is 'optional'
	https://github.com/MDEGroup/sirius-coevolution/tree/1.1

	Case 1.2 : The new class is 'mandatory'
	https://github.com/MDEGroup/sirius-coevolution/tree/1.2

Case 2 : Add Empty, Abstract Class
https://github.com/MDEGroup/sirius-coevolution/tree/2	

Case 3 : Add Specialization
https://github.com/MDEGroup/sirius-coevolution/tree/3

Case 4 : Delete Concrete Class
https://github.com/MDEGroup/sirius-coevolution/tree/4

Case 5 : Rename Class
https://github.com/MDEGroup/sirius-coevolution/tree/5

Case 6 : Add Property

	Case 6.1 : Add Attribute
	https://github.com/MDEGroup/sirius-coevolution/tree/6.1

	Case 6.2 : Add Reference
	https://github.com/MDEGroup/sirius-coevolution/tree/6.2

Case 7 : Delete Property
	
	Case 7.1 : Delete Attribute
	https://github.com/MDEGroup/sirius-coevolution/tree/7.1

	Case 7.2 : Delete Reference
	https://github.com/MDEGroup/sirius-coevolution/tree/7.2

Case 8 : Rename Property

	Case 8.1 : Rename Attribute
	https://github.com/MDEGroup/sirius-coevolution/tree/8.1

	Case 8.2 : Rename Reference 
	https://github.com/MDEGroup/sirius-coevolution/tree/8.2

Case 9 : Move Property

	Case 9.1 : Move Attribute
	https://github.com/MDEGroup/sirius-coevolution/tree/9.1

	Case 9.2 : Move Reference
	https://github.com/MDEGroup/sirius-coevolution/tree/9.2

Case 10 : Pull Up Property

	Case 10.1 :  Pull Up Attribute
	https://github.com/MDEGroup/sirius-coevolution/tree/10.1

	Case 10.2 : Pull Up Reference 
	https://github.com/MDEGroup/sirius-coevolution/tree/10.2

Case 11 : Change Property Type

	Case 11.1 : Change Attribute Type
	https://github.com/MDEGroup/sirius-coevolution/tree/11.1

	Case 11.2 : Change Reference Type
	https://github.com/MDEGroup/sirius-coevolution/tree/11.2


Big Number Arithmetic
=======================

Current hardware support 64 bit arithmetic operations which can handle maximum of 19 digits in base 10. 
This project overcomes that limitation and performs arithmetic operations on arbitrarily large numbers.

##Install

This library has the implementation of Big Number Arithmetic in Java, The following code snippet shows how 
to use the library

    BigNumberOperation bigNum=new BigNumberOperation();

###Input
	(((267611489478248274687641531761249149611414^45)-(267611489478248274687641531761249149611413^45+
	12743871264))*(876812361276127617761498412+1274334563))+(((26761148947824827468764153176124914961
	1414^45)-(267611489478248274687641531761249149611413^45+12743871264))*(876812361276127617761498412+
	1274334563))

All inputs must be given in infix order. And the parenthesis should be properly closed.

###Output
	 509751372908472442250047848400049362649854042438079616005507840019599241894785548057492267792569
	 593864159376030765038019224588667490769684359146349633504603186381452386695816733757616420230367
	 119042827518595661422420136820584986358878838534206397869716079766019980443047831838362645830449
	 186984141432174531691792996331308124271161632394811361374283668164741686837403767712675492785620
	 928250465846834214186566434901268649068710270244178852461502079241190966097231236334744534171367
	 670742293778327557976286439209459406666779542912611167906437062902662948070676272167384519612842
	 829290822798161964259908514465811710269746745267823803452899202384581737654960689051321986177875
	 422852010107749250628661630519288090227345724014867494431919125978525720832482153964528037001973
	 585005276805929219978230272882868846871715537565055534791801602621353207068671021378653551950662
	 241340670559525813161582497330404930469330667407162800533793147398203135818476845349963560197831
	 425060099839798942037216520637856706657226466958443379763225417220868667094266274807850730392497
	 553904841299372051162845547379906962597136585126394637297155287467453246863961522288013019006930
	 129505465130072272927534996097946095078318093333517124197330860346830188597105120931859670265299
	 958101718325265901958329048620379790867983033828284672558050021816268603291722056322391844928561
	 403762631042407307435690651039944560338202267871400001338337135342571738808112373800824636732141
	 029014660961078381998902506075371352302616896278848000388638841343324277566939437214614648175118
	 192494057529825291780661315426551956069197686672361250687113601591155702103775940224278144937119
	 586439644316636875983435680101439831498623287853378898027123877326933545322116102854179840977827
	 437318969424828606397610092824704148257537878107118642059200627030339697848954528942703529265625
	 6025930924181079117613068650
	 
	 Output is a single number
  
##Project Contributor

* Dinesh Appavoo ([@DineshAppavoo](https://twitter.com/DineshAppavoo))

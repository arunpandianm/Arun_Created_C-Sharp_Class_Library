This class library was created by arunpandian for practise purpose...
Portfolio website: http://www.arunpandianm.com

How to Add Class Reference:
Step 1: Goto Solution Explorer in Visual Studio
Step 2: Right Click on Reference folder and select "Add Reference"
Step 3: Click on "Browse Tab"
Step 4: Browse to ArunFlames.dll and Click Ok

How to Used it:

Step 1 : type the "using ArunCalc; above the namespace"  //without quotes
Step 2 : Create an object for "ArunFlamesLibrary"
		for example : ArunFlamesLibrary myObject = new ArunFlamesLibrary();
			      myObject.flames("arunpandian", "selvi");

Helper Method of ArunFlamesLibrary:

1==> flames("boy_name", "girl_name")
2==> normalizeTwoString("String One", "String Two")
3==> stringCheck("String One", "String Two")
4==> unCommonLetters("My String")
5==> findFlames(5)
6==> flamesDetail("boy_name", "girl_name"); //Note: flamesDetail will work only in console application.

Explanation:

1# flames("boy_name", "girl_name")
	return "relationship" //(i.e. Love) //returns string

2# normalizeTwoString("String One", "String Two")
	return "stringonestringtwo" //returns string 
	//Combines two string.
	//Remove whitespaces.
	//convert to lowercase.

3# stringCheck"boy_name", "girl_name")
	return "NoProblem" //returns string
	Generate error message if //both names are same.
				  //passing empty parameters.

4# unCommonLetters("My String")
	return "mystring" //return string
	//it remove whitespace.
	//convert to lowercase.
	//finds the common pair letters and remove them both.

5# findFlames(5)
	return "0L0000" //return string
	//give count of uncommon letters and find your flames.

6# flamesDetail("boy_name", "girl_name"); 
	return "relationship" //(i.e. Love) //returns string
	//Note: flamesDetail will work only in console application.
	//It details lot of information.
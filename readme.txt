Team_Fury Script Tester

Introduction:

Team_Fury Script Tester is for testing scripts written in Javascript, PHP and Python. 
It reads the output of the script, performs a regex check on it, and streams the result.


The result can be streamed in 2 forms :

	a. This will display all the results in valid JSON:

		hostsite-url/team-fury/index?php 
   

	b. This will display all the results in basic html:

		hostsite-url/team-fury/index.php



The outcome/status of the test on each script is either :

	1. Successful : if the output of the script meets the requirement.

	2. Failed : if the output of the script does not meet the requirement.



Requirement : Hello World, this is <Full Name> with <HNG ID> and email <Email> using <Script Language> `<for>` <Stage ?>

	Example :

		Success :
			Hello World, this is `John Doe` with HNG ID : `0098` and email : `johndoe@gmail.com` 
			using `javascript` for Stage `2`.

		Failed :
			Hello World, this is John, i'm a HNG intern and my email address is : `johndoe@gmail.com`. 
			I am using javascript to complete the task and be promoted to Stage 2.



Getting Started

	a. Create a file in the scripts folder with any of the mentioned programming languages (JavaScript, PHP and python).

	b. Support for other languages will be be in future updates.

	c. Fork the repository to your github account and clone

		git clone https://github.com/youraccount/team-fury-1.git && cd team-fury-1

	d. After cloning, navigate to the script folder and create a file file `username.(js,py,php)`

	    	cd scripts

	e. Run the following codes to commit your changes

    		i . 	git branch [branchname]
	    	ii. 	git checkout [branchname]
    		iii.	git add .
	    	iv.	git commit -a -m "your commit message"
    		v. 	git push origin [branchname]

	f. Proceed to your online repository and create a pull request


Contributing

	Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

	Please make sure to update tests as appropriate.


License

	MIT - https://choosealicense.com/licenses/mit/


Happy Hacking!!!
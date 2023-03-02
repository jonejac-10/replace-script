# replace-script
## replace

The objective of the "replace" file is to simply replace oldpattern, which is DevOps, with newpattern, which is WebApp. First, it will open path, and if it contains oldpattern, it will replace it with newpattern. Once it was replaced, we will write the newpattern into path. If path does not exist, obviously we will be unable to replace oldpattern with newpattern so it will print to the screen that {pathname} does not exist. Once the replacement is finished, after making the file executable, we will be able to run the code by stating ./replace test DevOps WebApp. This should replace the "DevOps" in the files DevOps.java and DevOpsMain.java with "WebApp". Then find test and open the files to find out if it worked.

## run-test

The main objective of the "run-test" file is to test to see if the replacement occurs and create/remove the test/edu/bvu/cs directory to execute the code in. In the run-test file, you have to illustrate the two commands necessary to run the code, those being "setup" and "teardown". If you call "setup", the directory "test/edu/bvu/cs" and the files "DevOps.java" and "DevOpsMain.java" will be created and a usage message will be printed on the screen signaling that the setup has been completed. From then on, make the file executable and test to see if the code works and a replacement is made. Once the setup is completed, if you run the code it should list the directories and files on the screen. If "teardown" is called, it simply removes the test directory and everything that comes along with it.

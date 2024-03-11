## sbt project compiled with Scala 3

### Usage

This is a normal sbt project. You can compile code with `sbt compile`, run it with `sbt run`, and `sbt console` will start a Scala 3 REPL.

For more information on the sbt-dotty plugin, see the
[scala3-example-project](https://github.com/scala/scala3-example-project/blob/main/README.md).

### Usage with VSCode

Be sure you have installed VSCode extensions for Scala (Metals) and Scala syntax (official).

Upon opening the project, a prompt will appear in the bottom right corner requesting to Import build. Please select this option.

![image](https://github.com/mviroli/mviroli-public-pps-code-scala/assets/23448811/c40a235b-4b53-4f51-8e60-8f13eb74c367)

Following this, a notification indicating that the sbt project is importing will appear.

![image](https://github.com/mviroli/mviroli-public-pps-code-scala/assets/23448811/2807fe6d-afdd-42ca-9fb1-357ed3d02920)

Next, navigate to a Scala file that extends App. For example, by opening the Values file and clicking the run button located at the top of the file, you will initiate the execution of the code. The output of this operation can be observed in the bottom section of VSCode.

![image](https://github.com/mviroli/mviroli-public-pps-code-scala/assets/23448811/14bb0cff-b3d1-4548-bbab-558d754b2124)

Additionally, access the test file located at src/test/scala/u02/TuplesTest.scala. Here, you will find a green arrow on the left side, enabling you to run the tests. Initiating the first test will execute all the tests, and the results will be displayed accordingly.

![image](https://github.com/mviroli/mviroli-public-pps-code-scala/assets/23448811/96559a7c-f072-405d-9fdd-4dbd0a399d14)

![image](https://github.com/mviroli/mviroli-public-pps-code-scala/assets/23448811/84049cfe-10d4-40f2-b7f1-fa9d9c3ed100)

![Corda](https://www.corda.net/wp-content/uploads/2016/11/fg005_corda_b.png)

# Example CorDapp

Welcome to the example CorDapp. This CorDapp is documented [here](http://docs.corda.net/tutorial-cordapp.html).

## Running the example

Make sure that you have the latest gradle

Deploy the nodes from terminal using `./gradlew deployNodes` on mac or `gradlew.bat deployNodes` for windows.

Then run the example cordapp using the kotlin-source by running `kotlin-source/build/nodes/runnodes` for mac or `call kotlin-source\build\nodes\runnodes.bat` for windows.

## Accessing Nodes

With the example running you may access each node through a browser:

PartyA - `http://localhost:10009/web/example/`
PartyB - `http://localhost:10012/web/example/`
PartyC - `http://localhost:10015/web/example/`

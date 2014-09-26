# gearman-tools

What are the simplest-and-dumbest tools for testing a Gearman setup?

## publish

	gearman-tools$ ./bin/publish 
	Send data: hello world
	Send data: will you be my friend
	Send data: 

## subscribe

	gearman-tools$ ./bin/subscribe
	INFO:root:{"input": "hello world", "timestamp": 1411762743.861222}
	INFO:root:{"input": "will you be my friend", "timestamp": 1411762748.337091}

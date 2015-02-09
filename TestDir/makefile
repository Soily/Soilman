all:
	g++ -g -c -D_REENTRANT -pthread -I$CPPUTEST_HOME/include SprintfTest.cpp
	g++ -g -c -D_REENTRANT -pthread -I$CPPUTEST_HOME/include AllTests.cpp
	g++ -o Test SprintfTest.o AllTests.o -L$CPPUTEST_HOME/lib -lCppUTest -lCppUTestExt -lpthread	
clean:
	-rm SprintfTest.o
	-rm AllTests.o
	-rm Test

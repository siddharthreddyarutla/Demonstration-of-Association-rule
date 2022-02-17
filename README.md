# Demonstration-of-Association-rule
This experiment illustrates some of the basic elements of asscociation rule mining using WEKA. The sample dataset used for this example is test.arff

<H1>Aim: </H1>
This experiment illustrates some of the basic elements of asscociation rule mining
using WEKA. The sample dataset used for this example is test.arff

Step1: Open the data file in Weka Explorer. It is presumed that the required data fields have
been discretized. In this example it is age attribute.

Step2: Clicking on the associate tab will bring up the interface for association rule algorithm.

Step3: We will use apriori algorithm. This is the default algorithm.

Step4: Inorder to change the parameters for the run (example support, confidence etc) we
click on the text box immediately to the right of the choose button.

<H1>Dataset test.arff</H1>

@relation test
@attribute admissionyear {2005,2006,2007,2008,2009,2010}
@attribute course {cse,mech,it,ece}
@data
%
2005, cse
2005, it
2005, cse
2006, mech
2006, it
2006, ece
2007, it
2007, cse
2008, it
2008, cse
2009, it
2009, ece
%

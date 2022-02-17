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

@relation test<BR>
@attribute admissionyear {2005,2006,2007,2008,2009,2010}<BR>
@attribute course {cse,mech,it,ece}<BR>
@data<BR>
%<BR>
2005, cse<BR>
2005, it<BR>
2005, cse<BR>
2006, mech<BR>
2006, it<BR>
2006, ece<BR>
2007, it<BR>
2007, cse<BR>
2008, it<BR>
2008, cse<BR>
2009, it<BR>
2009, ece<BR>
%<BR>

  <H1>OUTPUT:</H1>
  
  
  ![image](https://user-images.githubusercontent.com/70971734/154476094-d60442bf-b48d-4954-942f-9512900e87ed.png)
  
  <HR>
  
  ![image](https://user-images.githubusercontent.com/70971734/154476213-edee736d-ded5-40ea-b7dd-6f215a3f1a50.png)


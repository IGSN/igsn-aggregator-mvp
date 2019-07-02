# IGSN aggregator MVP

## About

So presently the test aggreator is the NSF EarthCube Gleaner code.
You can find the Gleaner code at 
https://github.com/earthcubearchitecture-project418/gleaner .

We will generate a config file for the test provider sites and
use Gleaner to test approaches to how an aggregator works and the 
loads.  

The output of these runs will form a semantic network like being
created for EarthCube Council of Data Facilities. 
(ref: https://github.com/earthcubearchitecture-project418/CDFSemanticNetwork )

From that,  different indexes can be generated that address 
performances and use goals.   

Note, a large scale aggrator might use something like Apache Nutch.  
However, that is an approach with many dependancies.  
Gleaner is a single binary and it is easy to deploy the support tools 
with Docker.   

An early test site was created at http://samples.earth and the 
code for that can be found at: https://github.com/fils/samplesEarth

However, that approach is deprecated by the IGSN Provider MVP 
at https://github.com/IGSN/igsn-publisher-mvp


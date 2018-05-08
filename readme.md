How-To Documentation:
Requirements:
  Linux OS (Ubuntu 16.04.3 LTS), Java 1.8, Git
Clone GitHub Repository:
   git clone https://github.com/CSCI-362-01-2017/NBA
Navigate to the TestAutomation folder
  cd TestAutomation
Execute scripts/runAllTests.sh to run the source framework and open the html file in the default browser.
  sh ./scripts/runAllTests.sh
Navigate to the scripts folder, then rename "NumberUtils.java" to "SourceNumberUtils.java"
Rename "FaultedNumberUtils.java" to "NumberUtils.java" this will make the ACTIVE class, the faulted class. 
Rerun the script.
  sh ./scripts/runAllTests.sh

Here below the steps to install pyspark for Mac M1 chip if you encounter with:

1. Make sure you have Homebrew, else install Homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2. Install X-code
xcode-select –-install

3. Install Java8 through the official website (not through terminal)
https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

4. Install Apache-Spark
 brew install apache-spark 

5. Install Pyspark and Findspark (if you have anaconda)
conda install -c conda-forge findspark 
conda install -c conda-forge/label/gcc7 findspark
conda install -c conda-forge pyspark


  710  sudo  apt-get update
  
  712  sudo add-apt-repository ppa:webupd8team/java
  
  713  sudo  apt-get update
  
  714  sudo apt-get install oracle-java8-installer -y
  
  715  java  -version
  
  716  cd ..
  
  717  sudo  mkdir /opt/maven36
  
  718  tar -zxvf ~/Downloads/apache-maven-3.6.0-bin.tar.gz  -C /opt/maven36/
  
  719  sudo tar -zxvf ~/Downloads/apache-maven-3.6.0-bin.tar.gz  -C /opt/maven36/
  
  720  cd /opt/maven36/
  
  723  sudo mv apache-maven-3.6.0/* .
  
  725  sudo rmdir apache-maven-3.6.0/
  
  727  sudo vim /etc/profile.d/mavenenv.sh
  
  ##export M2_HOME=/opt/maven36
  
  ##export PATH=${M2_HOME}/bin:${PATH}
  
  728  sudo chmod +x /etc/profile.d/mavenenv.sh
  
  732  source /etc/profile.d/mavenenv.sh 
  
  733  mvn --version
  
  734  cd 
  
  735  cd codehub/
  
  737  cd basic_maven_project/
  
  740  mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4

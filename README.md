#Asterix Demo Environment

This Vagrantfile fetches the latest version of AsterixDB from the website, and starts it with two NCs inside of one Debian-based VM. 

##Running/Usage

    vagrant up
Then, visit http://10.42.0.2:19001 to view the AsterixDB web interface. All other APIs will be listening from the CC on that address as well. To follow the ADM/AQL 101 Demo, simply put any files that need to be accessed by the Asterix instance in the same folder as the Vagrantfile and they will appear inside of the VM under the /vagrant directory. 

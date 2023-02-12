## AirBnB clone project ##

This project about the prototype of the AirBnB website                                                                                  
so we will be creating a firstly a console that will read a line of command                                                             
personally for the project and we will build an object that will read different                                                         
class into the website. Also we will create an api and a restful api using Flask                                                       


        * What is a command interpreter: It is a prompt just like                                                                       
          the shell that read different type of command but this is used for a particular project                                       
          for specific task.                                                                                                            

                                                                                                                                       
        * How does command interpreter start: It start by importing the cmd library in python and                                       
          call it in a class with definition of different variable in the class                                                         
                                                                                                                                        
        * How does command interpreter end: It end when all variable is called we then we will link                                     
          our variables to the class so that it can be callable                                                                         
                                                                                                                                        ### A sample of the command interpreter ###                                                                                          
===============================================                                            
	import cmd                                                                                                                              
                                                                                                                                        
	class HelloWorld(cmd.Cmd):                                                                                                              
        	"""This will greet my friends"""                                                                                                
        	FRIENDS = ['Ayo', 'Femi', 'Miracle', 'Afeez']                                                                                  
                                                                                                                                                	def to_greet(self, person):                                                                                                     
                	if person and person in self.FRIENDS:                                                                                   
                        	print ('Hi %s!' & person)                                                                                       
                	elif person:                                                                                                            
                        	print('Hello' + person)                                                                                         
                	else:                                                                                                                   
                        	print('Hello')                                                                                                  

                                                                                                                                        
if __name__ == '__main__':                                                                                                              
        HelloWorld().cmdloop()

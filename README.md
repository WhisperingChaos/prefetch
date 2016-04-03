# prefetch

###Terms
####COMMAND
An abstraction supporting both the preperation for and execution of a process.  
#####Execute() - A method encapsulating all the elements needed by a COMMAND to run it as a process.
#####Prefetch() - A method encapsulating all the elements necessary to prepare a COMMAND to speed its Execute method.

####PREFETCH
An abstraction to support the acceleration of one or more [COMMANDs](#command).  Acceleration refers to any preprocessing that can be accomplished before [Executing](#execute) the COMMAND.
#####Display() - A method that reports on all the COMMANDs currently known by PREFETCH.
#####Remove( COMMAND )|( ALL ) - A method that removes the identified COMMAND from the PREFETCH.
#####Execute( COMMAND ) - A method executing the provided COMMAND.


# Agents and Environment 

## **Agent**
- Agent: Something that acts 
- is anything that can be viewed as perceiving its environment through senosrs and acting upon that environment through actuatos
- agent gets percepts one at atime and maos this percept sequence toa ctions 

## **Rational agent**
- is one that acts so as toachieve the best outcome opr, where ther is uncertainty, the best expected outcome 

## **Intelligent Agent**
- is one that is capble of doing following things autonomously 
  - perceive environment respond to change that occur in order to satisfy design objectives
  - interact with other agent and to satify design objective 
  -  needs to be goal directed as well as reacive
- it does things based in resoning, while rationall means it does the best action for agiven sitation

## **property of an agent**
 - autonomous
 - interact with other agent plus the environment 
 - reative to the environment 
 - pro-active (goal oriented)
 
## the concept of rationlaity
- a rational agent is one that does the right thing 
- right thing are the actions that will casue the agent to be most successful
- therefore we need some measurement of sucess for an agent 
- performance measures are the criterion for success of an agent behaviors
- eg: performance measure of a vaccume-cleaner agent could be 
  - amount of dirt cleaned up
  - amount of time taken 
  - amount of electircity consumed
  - amoount of nouse generated 
- is not easy task to choose the performance measure of an agent 
- As a general rule, it is better to design performance measures according to what one actually wants in the environment, rather than according to how one thinks the agent should behave.
- what is rational at a given time depends on four things 
  1) The performance measure thaty defines the criterions of success
  2) the agent's prior knowledge of the envireonment 
  3) the action that the agent can perform 
  4) the agent's percept sequence to date 
- foar each possible percept sequence, a rationaal agent should select an action that is expected to maximize its performace m,eauer, given the evidence provided by the percept sequence and whatever built-in-knowldge the agent has 
- chooses whichever actiona maximizes the expeted value of the performance measuiere given the sequence to date abd prior environment knowledge 

## Environment and it properties 
- to design a rational agent we must specify its task environment
- task environment are essentially the "problems" to which rational agent are the "solutions"
- the flavor of the task environemnt directly affect the appropriate design for the agent program
- in designing an agent, the first setp must always be to specify the task environment as fully as possible 
- it is specified by PEAS (perforamce, Environment, Actuators, Sensors) 
  - Performance: Safe, fast, legal, comfortable trip, maximize profits
  - Environment: Roads, other traffic, pedestrians, customers
  - Actuators: Steering, accelerator, brake, signal, horn, display
  - Sensors: Cameras, sonar, speedometer, GPS, odometer, accelerometer,engine sensors, keyboard

# Properties of Environment (types/classes of environment) 
1) Fully observable vs partially observable
  - agent’s sensors give it access to the complete state of the environment at each point in time, then we say that the task environment is fully observable.
  - partially observable because of noisy and inaccurate sensors or because parts of the state are simply missing from the sensor data
3) Single agent vs multiple agent
4) Deterministic vs stochastic
5) Episodic vs sequential
6) Static vbs dynamic
7) Discrete vs continuous
8) Known vs unknown 

## The strucuture of agent 
- agent = architecture + program
- The program we choose has to be one that is appropriate for the architecture. If the program is going to recommend actions like Walk, the architecture had better have legs.
- The architecture might be just an ordinary PC, or it might be a robotic car with several onboard computers, cameras, and other sensors.
- the architecture makes the percepts from the sensors available to the program, runs the program, and feeds the program’s action choices to the actuators as they are generated

### Types of agent (agent Programs)
1) Simple reflex agents
2) Model-based reflex agent 
3) GOal-based agents 
4) Utility-based agents
5) Learning agents 



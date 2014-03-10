CE3
===

computer exercise # 3: State Machine

#Moore State Machine
![Moore](https://raw.github.com/jrecheverry/CE3/master/moore_testbench.png)

In a Moore state machine outputs depend on the current state only. The outputs of a Moore state machine change at the clock edge. Moore machines tend to be synchronous, meaning that changes occur with the clock. As noted above, the state, elevator floor you are on, will change with the rising edge. The above image of the moore state machine is correct because the next state changes with the rising edge.

#Mealy State Machine
![Mealy](https://raw.github.com/jrecheverry/CE3/master/Mealy_testbench_Echeverry.png)

In a Mealy state machine outputs depend on the current state and inputs.
Mealy state machines tend to be asynchronous, meaning the input can change without the clock and it can cause output change as soon as logic is done. The above image of the mealy state machine is correct because the next state does not depend on the clock's rising edge.

# Distributed Architecture

## Timing Model
 The  __synchronous model__ is the simplest: Components take steps simultaneously; The time for a message to be delivered is usually known, and we can assume the speed of each process.
 This model is not realistic but useful to achive theoretical results that later con be tanslated to another model.

 The __asynchronous model__: Component take steps in whatever order; Doesn't offer any guarantee about the speed in which step will be taken. One example of imposibility results, The [“Impossibility of Consensus with one Faulty Process](http://cs-www.cs.yale.edu/homes/arvind/cs425/doc/fischer.pdf)

The __partially synchronous model__: Components have some information about timing, having access to almost synchronised clocks, or they might have approximations of how long messages take to be delivered, or how long it takes a processes to execute a step.

## Interprocess comunication


## Networking

* [Fallecies of Distributed computing](http://www.rgoarchitects.com/Files/fallacies.pdf)
  1. The network is reliable.
  2. Latency is zero
  3. Bandwidth is infinite
  4. The network is secure
  5. Topology doesn't change
  6. There is one administrator
  7. Transport cost is zero
  8. The network is homogeneous

## To Read
* [Distributed Algorithms by  Nancy A. Lynch](http://www.amazon.com/Distributed-Algorithms-Kaufmann-Management-Systems/dp/1558603484)
* [Scaling Stateful Services resource links by @caitie](https://github.com/caitiem20/scalingstatefulservices)
* [Learning about distributed systems by Alvaro Videla](http://videlalvaro.github.io/2015/12/learning-about-distributed-systems.html)

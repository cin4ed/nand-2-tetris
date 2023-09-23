---
title: "Sequential Logic"
author: "Kenneth de Guadalupe Quintero Valles"
date: "09/22/2023"
abstract: "YAML"
---

# Sequential logic

In automata theory, sequential logic is a **type of logic circuit** whose output depends on the present value of
its input signals and on the sequence of past inputs, the input history. This is in contrast to combinational
logic, whose output is a function of only the present input. That is, sequential logic has state (**memory**) 
while combinational logic does not.

Sequential logic is used to construct finite-state machines, a basic building block in all digital circuitry.
Virtually all circuits in practical digital devices are a mixture of combinational and sequential logic.

A familiar example of a device with sequential logid is a television set with "channel up" and "channel down"
buttons. Pressing the "up" button gives the television an input telling it to switch to the next channel, for
this, the television has to know what is the current channel it is in. Therefore the television stores the
current channel as part of its state. So when "channel up" or "channel down" is pressed, the sequential logic
of the channel selection circuitry calculates the new channel from the input and the current channel already
stored.

Digital sequential logic circuits are divided into **synchronous** and **asynchronous** types. In synchronous 
sequential circuits, the state of the device changes only at discrete times in response to a clock signal.
In asynchronous circuits the state of the device can change at any time in response to changing inputs.

## Furthermore

- Synchronous logic
- Asynchronous logic


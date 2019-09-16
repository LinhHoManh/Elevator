# Elevator

## To get a C, you need to:
### Elevator showcase from Electrical Engineering Center
- [x] Find an elevator in the apartment/campus/hotel. Only one example for each student (below)
<p align="center">
<img src="https://github.com/Alex-Nguyen/Elevator/blob/master/lift.gif" width="200px">
</p>

- [x] Take photos of the control interface (above)
- [x] Show a gif image of the control interface in operation (above).
- [x] Find the issues with the current design.
    + Door automatically closes without warning users
    + Floor buttons align horizontally
    + No spatial relationship between floor number and the actual floor
    + No indicator to show the current floor we are in
    + Don't know when the door will be closing
    + No estimated time of arrival to the desire floor
- [x] Explain why it is bad
    + Door automatically closes without warning users => unaware users may face problem (e.g., dropping coffee)
    + Floor buttons align horizontally => not follow the design convention
    + No spatial relationship between floor number and the actual floor => not follow the design convention
    + No indicator to show the current floor we are in => want to floor 4, elevator is still in floor 3, door opens, I think I'm in 4th floor
    + Don't know when the door will be closing => this happens a lot, hit the close button and wait for 3 minutes, door not closes due to internal problem.
    + No estimated time of arrival to the desire floor (optional). => it's better to know how much time we reach the destination so we can better plan our moving time.

## To get a B, you need to:
- [x] Think about the common things that you use an elevator. List your most common uses and other more rare uses. Does the interface make doing those common things easier?
    + Common things: Hit the desired floor button many times (to make sure that the button is pressed); Press the close door many time with expect that the door will close faster
    + Rare uses: Emergency buttons (Call operator, fire alarm)
- [x] Think about how the user interacts with the elevator. What is the common sequence of actions?
    + Hit the desired floor/door close many times. Nothing change in terms of operation
- [x] How does the elevator support the user figure out how to make it work?
    + Light on the button indicates that the corresponding floor is pressed
    + Sound is played once the elevator reached a floor (only to notify users)

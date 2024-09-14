# The Signal

The signal is an object used to distribute messages across the application.

## Mode 1

widget can have one or more signals,
when a widget wants it can trigger one of its signals with an data bind to it
then that data will be shred among anything that was subscribed to the signal

> Note:
> you can use the [SignalModule](https://github.com/EliaOndacs/signals)

## Mode 2

widget can have one or more signals, and each signal can have one or
more slot functions'
a widget can emit one ot its signals among with a data that will be
passed into the first argument of the slot function for each slot
function that the signal have stored

> Note:
> [example implementation](https://github.com/EliaOndacs/TENT) has a this mode implemented

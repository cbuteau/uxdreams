
# Login

## Problems

1. Error handling always blames the user.
  a. It could be the service times out.
  b. It could be unforeseen things.

## Strategies

Classify errors and route them through something that bubbles different errors based on application state and other factors.

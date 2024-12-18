# Starknet: Counter smart contract (Using Cairo Programming Language)

A simple counter smart contract built on Starknet that demonstrates basic storage management, events, and access control. The contract allows users to increment and decrement a counter value, while maintaining ownership controls.

## Features of This Contract

-   It gets the current counter value
-   You can increase the counter by 1
-   You can decrease the counter by 1 (and also there's a checker to ensure it prevents the calc of negative values)
-   As the owner, you can reset the counter
-   Upon the completion of each function, events are emitted so as to track changes that occur
-   OpenZeppelin Ownable component was as well used to carry out Access Control.

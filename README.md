# Sque-bytecode
Sque (Scratch QUEue) - Custom bytecode which uses Queue data structure and has interpreter in Scratch
# Documentation
Uses queue and tape. Tape indexes start at 0
"str" - enqueue string str

'123' - enqueue integer 123

t - enqueue true

f - enqueue false

+-*/% - dequeue integers a and b, enqueue a<op>b

, - ask for input and enqueue it as a string

 . - dequeue and output on a new line

=<> - deque a and b, if a<cond>b is true enqueue true, else enqueue false

; - dequeue integer and jump to the n-th : where n is the integer

! - dequeue boolean and an integer, if false ; instruction is executed

g - dequeue index and a value, set value at cell with that index to a value. 

p - dequeue index and enqueue value of cell with that index

^ - dequeue and enqueue

\# - deque and output on the same line

~ - dequeue string and an integer, enqueue n-th letter of a string, where n is the integer

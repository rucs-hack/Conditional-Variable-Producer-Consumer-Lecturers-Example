# Conditional-Variable-Producer-Consumer-Lecturers-Example

I wrote this to teach Circular Buffers to my students.
The language used is ANSI C. In order to simplify its use as a demonstration tool the text sent through the buffer is a hard coded string. This is passed to the main function so can be replaced with a file, and was in the assignment this was preperation for.
Alterations would be required, such as file end checks instead of knowing the exact character count. These were ommitted from this demo, or rather removed and replaced with a fixed count in order to give my students something to do while converting this code to the specified language and adding to it in order to meet their assignment requirements.

As it stands this is a useful tool if you're trying to understand either Conditional Variables in C or Producer Consumers. This uses basic Pthreading and has only been compiled on Linux.

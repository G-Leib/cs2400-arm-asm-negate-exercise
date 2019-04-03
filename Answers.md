## UAL
UAL stands for Unified Assembler Language

**Question 1** What is the short program doing that the long program is not?

1. Answer: The short program is rewriting the positive values back into memory whereas the long program only puts the positive values onto the stack.
        
**QUESTION 2:** Why do you think the compiler has generated such assembly code?

2. Answer: The compiler generates this code because memory was not allocated and the array was created as a locally in main so it is only stored on the stack.

**QUESTION 3:** How would you try to change the code so that the compiler would generate an assembly program that behaves more like the short one above?

3. Answer: To solve this use malloc to allocate memory for the array and use pointers to change the values at each address.

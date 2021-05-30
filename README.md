# DDK_bootloader_testing_tool
<br><br/>

## Features
* Simulate bootloader by eliminating hardware and using substituted function with abstract architecture. 
<br><br/>

## All the thinking are following bellow,
1. We need a sample bootloader of c code.
2. Make sure all the functoin are correct and can be compiled.
3. Focus on the funcion if it calls something with registers.
4. We should use some tech to simulate these regisers and all the others also.
5. To sum up, we should change the interrupt function and registers address to another way, such as, a new function and new varriables and execute via threads.
6. ....
<br><br/>

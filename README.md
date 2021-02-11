# memory-leak-detector

<<<<<<< HEAD
## Project Development Phases

1. Structure Database  
   MLD library will maintain the information about all structures which the application using.

   - MLD library must know the information about all structures being used by the application.
   - It is the responsibility of the application to tell the MLD library during initialization about all structures it is using. This is called "structure registration"
   - MLD library will maintain the structure database(preferably a linked-list) to store application structure information.
   - Key to search in structure database is "name fo structure"

2. Object Database  
   MLD library will maintain the information about all objects malloc'd by the application.

3. Memory Leak Detection Algorithm  
   MLD library triggers Memory Leak Detection Algorithm on Object Database to find leaked objects.
=======
This library tracks all the memory allocated dynamically on the heap memory. Tracking memory allocation on heap memory helps C programmer to avoid memory leak and memory corruption.
>>>>>>> f98a99aa8b2800b18f5b6712d3534f086855d77c

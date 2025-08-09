## ACID Properties

1. **Atomicity**  
   All parts of a transaction happen or none do.  
   Example: Transferring money between accounts — both withdrawal and deposit must occur.

2. **Consistency**  
   Data remains valid before and after transactions.  
   Example: If a student's grades are updated, they must match allowed grading formats.

3. **Isolation**  
   Transactions do not affect each other until committed.  
   Example: Two professors updating different student grades at the same time won't interfere.

4. **Durability**  
   Once a transaction is committed, it stays saved, even after a crash.  
   Example: A student's paid tuition record remains after a system restart.

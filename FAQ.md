# Digital Electronics 2 FAQ

### Extract bitfield
You can extract a subset of wires from a bus x like this:  
    
    x(n, m)

Here it is important to know that n >= m, otherwise Chisel will throw a hard to understand error.

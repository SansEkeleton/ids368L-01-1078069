
# Realizar "Hello World" con el lenguaje asignado. 

print_string("Hello world")


# Demostrar como se interactúa con el Environment con el lenguaje asignado. 

###### Standard output

``` Reason

 let printStrings = () => {  
 print_endline("Hello");  
 print_endline("Mancos")  
 };  
 printStrings(); 
 
 ```
 
 ###### Variables de Ambiente.
 
 ```Reason
 let x: int = 5  
let y: int = 6  

print_int(x + y);  
```
###### File/IO
```Reason
let in_channel = open_in "lines.txt" in  
try  
  while true do  
    let line = input_line in_channel in  
    (* do something with line *)  
  done  
with End_of_file ->  
  close_in in_channel  
```

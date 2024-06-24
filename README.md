## How to Reproduce the Crashes?
1st way (input via stdin):
  1. Compile the modified code with "cargo b" keyword in root directory 

  2. Run the binary with given inputs in "fuzzer_input" directory (e.g. "./target/debug/grex < ./fuzzer_input/id:000011*")

2nd way <input via file(not modified code)>
   1. Compile the modified code with "cargo b" keyword in root directory 

   2. Run the binary with given inputs in "fuzzer_input" directory (e.g. "./target/debug/grex --file ./fuzzer_input/id:000011*") 

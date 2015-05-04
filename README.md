# cpm
basic package manager for C projects

### cpm new_package packagename

### cpm new_module packagename modulename

### cpm edit_module packagename modulename

### cpm h
  show all header folders with -I prefix

### cpm o 
  show all object files

### cpm run 
  gcc `cpm h` -o program `cpm o`


On the maintainer’s system:  
    
  **aclocal** _# Set up an m4 environment_  
  **autoconf** _# Generate configure from configure.ac_  
  **automake --add-missing** _# Generate Makefile.in from Makefile.am_  
  **./configure** _# Generate Makefile from Makefile.in_  
  **make distcheck** _# Use Makefile to build and test a tarball to distribute_  
    
On the end-user’s system:  
  
  **./configure** _# Generate Makefile from Makefile.in_  
  **make** _# Use Makefile to build the program_  
  **make install** _# Use Makefile to install the program_  



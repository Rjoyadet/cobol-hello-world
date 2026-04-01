# cobol-hello-world
looking at a simple phrase in cobol 

## how to run it locally (using GNU Cobol/ GnuCOBOL)
```bash
# Install compiler (on Ubuntu/Debian)
sudo apt install gnucobol

#compile
cobc -free -x -o hello-world hello-world.cob

# Run
./hello-world

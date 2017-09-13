to create and distribute .pex file
pex Fabric flask 'requests[security]' -o foo.pex -c fab -- startapp

to run the executable
./foo.pex startapp
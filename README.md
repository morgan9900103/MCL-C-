### Monte Carlo Localization C++

You will be able to observe the MCL in action through the generated images.

## Compiling the program

```
cd ~/YOUR_WORKSPACE
git clone https://github.com/morgan9900103/MCL-Cpp
cd MCL-Cpp
rm -rf Images/*
g++ main.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```

## Running the program

Before you run the program, make sure the ```Images``` folder is empty

```
./app
```

Wait for the program to iterate 50 times(or you can change the iteration times).

## Generated Images

After running the program, the images will be generated in ```Images``` folder

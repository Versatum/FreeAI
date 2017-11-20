# FreeAI
Free AI is a opensource project that attempt to develop a Artificial Inteligence framework.

![alt text](http://versatum.org/media/project/qGWdFpAOrCU2i6xW.jpg)


### Prerequisites

Compatible with GNU/C++ compiler. Other compiler not tested yet.

Intsall GNU/C++

For APT systems packages
```
sudo apt-get install g++
```

For YUM systems packages

```
yum install gcc-c++ 

```

Also you need cmake (2.8+) to compile it

```
wget http://www.cmake.org/files/v2.8/cmake-2.8.3.tar.gz
tar xzf cmake-2.8.3.tar.gz
cd cmake-2.8.3

./configure --help

./configure --prefix=/opt/cmake
``` 

To install it

```
make
make install
```

## Buiding the aplication

Go into the root project.
```
cd FreeAI
```

To build the aplication just run folllowing command. 
 

```
cmake .
make
```

Now just runt it!

```
./bin/FreeAI
```


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Eduardo Sant' Anna Martins** - *Initial work* - [eduardomartins](https://github.com/eduardomartins)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

# ECEPMP545

This is how your your workspace looks like, if you type the following command in your workspace

```bash
$ tree -L 4
```

``` bash
├── build
├── devel
├── README.md
└── src
    ├── CMakeLists.txt -> /opt/ros/kinetic/share/catkin/cmake/toplevel.cmake
    └── ta_pkg
        ├── bagfiles
        │   └── mybag.bag
        ├── CMakeLists.txt
        ├── package.xml
        ├── scripts
        │   ├── add_two_ints_client.py
        │   └── add_two_ints_server.py
        └── srv
            └── AddTwoInts.srv

```

The package I created is called `ta_pkg`, yours should be `beginner_tutorials` as specificed in Assignment 1.

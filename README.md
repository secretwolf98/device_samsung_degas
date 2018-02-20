# device_samsung_degaswifi
# Device configuration for Samsung Galaxy Tab 4 7"

## Spec Sheet
| Feature                 | Specification                     |
| :---------------------- | :-------------------------------- |
| CPU                     | Quad Core 1.2GHz                  |
| Chipset                 | Marvell PXA1088                   |
| Memory                  | 1.5GB RAM                         |
| Shipped Android Version | 4.4.2                             |
| Storage                 | 8/16GB                            |
| MicroSD                 | Up to 32GB                        |
| Dimentions              | 7.36 x 4.25 x 0.35 in             |
| Weight                  | 276 g                             |
| Display                 | 800 x 1280 pixels                 |
| Front Camera            | 1.3 MP                            |
| Back Camera             | 3.15 MP                           |
| Release Date            | May 2014                          |

## Device Picture
![Galaxy Tab 4 7"](http://cdn2.gsmarena.com/vv/bigpic/samsung-galaxy-tab-4-70.jpg "Galaxy Tab 4 7")



LineageOS 15.1
==============

Getting Started
---------------

To get started with Android for degaswifi, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).


You need to download JAVA to compile:

LineageOS 14.1: OpenJDK 1.8 (install openjdk-8-jdk)

LineageOS 11.0-13.0: OpenJDK 1.7 (install openjdk-7-jdk)*


Make your directories where the source code is kept:

mkdir -p ~/bin

mkdir -p ~/android/lineage


Make sure to repo the Google source code:

curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo

chmod a+x ~/bin/repo



To initialize your local repository, use a command like this:

    repo init -u git://github.com/secretwolf98/device_samsung_degaswifi -b lineage-15.1

Then to sync up:

    repo sync

Choose target:

    source build/envsetup.sh
    
    lunch degaswifi


To install the build:

    cd $OUT



Please see the LineageOS Wiki for building instructions.



## Copyright

```
#
# Copyright (C) 2017 The LineageOS Project
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
```


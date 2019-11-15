## Playing around with libmm-glib 

### Useful CLI history 
 
 2089  sudo apt install mmcli 
 2090  sudo apt install ModemManager 
 2091  sudo apt install libmm-glib 
 2092  sudo apt-get update 
 2093  sudo apt-get install modemmanager 
 2094  mmcli 
 2095  mmcli --version 
 2096  mmcli -L 
 2097  find / -name "libmm*" 
 2098  sudo find / -name "libmm*" 

 2101  sudo find /usr/ -name "libmm*" 
 2102  sudo apt-get install libmm-glib-dev 
 2103  ls /usr/include/libmm-glib/ 
 2104  ls -la /usr/include/libmm-glib/ 
 
 2108  cd /usr/include/libmm-glib/ 


 2116  find . -name "libmm*" 


 2123  ls 
 2124  mkdir libmm-glib-example 
 2125  cd libmm-glib-example/ 
 2126  ls 
 2127  git init 
 2128  gs 
 2129  touch main.cpp 
 2130  code main.cpp 
 2131  cd .. 
 2132  mv libmm-glib-example/ .. 
 2133  cd .. 
 2134  code libmm-glib-example/ 
 2135  cd libmm-glib-example/ 
 2136  gcc main.cpp 
 2137  gcc main.cpp -I=/usr/include/ 
 2138  gcc main.cpp 
 2139  find /usr/include/ -name "ModemManager" 
 2140  gcc main.cpp -I=/usr/include/ModemManager/ 
 2141  gcc main.cpp -I/usr/include/ModemManager/ -I 
 2142  gcc main.cpp -I/usr/include/ModemManager/ 
 2143  gcc main.cpp -I/usr/include/ModemManager/ -I/usr/include/libmm-glib/ 
 2144  sudo apt-get install gio 
 2145  find /usr/include/ -name "gio" 
 2146  find /usr/ -name "gio" 

 2148  sudo apt-get install libglib 
 2149  sudo apt-get search glib 
 2150  sudo apt-get install libglib2.0-dev 
 2151  uname -a 
 2152  dpkg 
 2153  dpkg -l 
 2154  dpkg -l libglib 
 2155  dpkg -l libglib2.0-dev 
 2156  sudo apt-get install --reinstall libglib2.0-dev 
 2157  ls -la /usr/include/glib-2.0/gio/gio.h 
 2158  gcc main.cpp -I/usr/include/ModemManager/ -I/usr/include/libmm-glib/ 
 2159  gcc main.cpp -I/usr/include/ModemManager/ -I/usr/include/libmm-glib/ -I/usr/include/glib-2.0/ 
 2160  find /usr/include/ -name "glibconfig" 
 2161  find /usr/include/ -name "glibconfig*" 
 2162  find /usr/include/ -name "glib*" 
 2163  find /usr/ -name "glib*" 
 2164  find /usr/ -name "glibconfig" 
 2165  find /usr/ -name "glibconfig*" 
 2166  gcc main.cpp -I/usr/include/ModemManager/ -I/usr/include/libmm-glib/ -I/usr/include/glib-2.0/ 
 2167  gcc main.cpp -I/usr/include/ModemManager/ -I/usr/include/libmm-glib/ -I/usr/include/glib-2.0/ -I/usr/lib/x86_64-linux-gnu/ glib-2.0/include/ 
 2168  g++ main.cpp -I/usr/include/ModemManager/ -I/usr/include/libmm-glib/ -I/usr/include/glib-2.0/ -I/usr/lib/x86_64-linux-gnu/ glib-2.0/include/ 
 2169  ./a.out 
 2170  echo "g++ main.cpp -I/usr/include/ModemManager/ -I/usr/include/libmm-glib/ -I/usr/include/glib-2.0/ -I/usr/lib/ x86_64-linux-gnu/glib-2.0/include/" > Makefile 
 2171  code Makefile 
 2172  make 
 2173  gs 
 2174  rm a.out 
 2175  gcm 'Compile a hello world program that includes libmm-glib' 
 2176  ga . 
 2177  gcm 'Compile a hello world program that includes libmm-glib' 
 2178  touch README.md 
 2179  code README.md 
 2180  history 
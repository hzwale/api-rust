sqlodbc.cpp
example: 
linux:
gcc -D_GLIBCXX_USE_CXX11_ABI=0 -std=c++11 wrapper.cpp -fPIC -shared -o libwrapper.a -I./include -DLINUX -L./bin/linux_x64/ -lDolphinDBAPI /usr/lib/x86_64-linux-gnu/libssl.so.1.0.0 /usr/lib/x86_64-linux-gnu/libcrypto.so.1.0.0 -luuid -lpthread -Wl,-rpath,./api-rust/src/bin/linux_x64

gcc -D_GLIBCXX_USE_CXX11_ABI=0 -std=c++11 wrapper.cpp -fPIC -shared -o libwrapper.a -I./include -DLINUX -L./bin/linux_x64/ -lDolphinDBAPI /usr/lib/x86_64-linux-gnu/libssl.so.1.0.0 /usr/lib/x86_64-linux-gnu/libcrypto.so.1.0.0 -luuid -lpthread -Wl,-rpath,./src/bin/linux_x64

  
gcc -D_GLIBCXX_USE_CXX11_ABI=0 -std=c++11 wrapper.cpp -fPIC -shared -o libwrapper.a -I./include -DLINUX -L./bin/linux_x64/ -lDolphinDBAPI -lssl -luuid -lpthread -Wl,-rpath,./api-rust/src/bin/linux_x64
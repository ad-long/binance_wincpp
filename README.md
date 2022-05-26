1. install vcpkg
git clone https://github.com/Microsoft/vcpkg.git
cd vcpkg
.\bootstrap-vcpkg.sh
.\vcpkg integrate install

2. install glog gtest gflags
.\vcpkg install glog gtest gflags

3. install openssl
download openssl: https://www.openssl.org/source/openssl-3.0.3.tar.gz
copy to vcpkg\downloads
.\vcpkg install openssl

4. install curl libwebsockets
.\vcpkg install curl libwebsockets

5. run
select x86 and build/run
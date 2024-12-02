## ROS Middlewares

Genel bilgi sahibi olunması açısından aşağıdaki linkler okunabilir.
ROS2 haberleşme için kullandığı DDS katmanı için farklı sağlayıcıları destekler.
Bu RMW'lerden birkaçı aynı sistemde yüklü olabilir. 



* [Different Middlewares](https://docs.ros.org/en/humble/Concepts/Intermediate/About-Different-Middleware-Vendors.html)
* [Working with multiple RMWs](https://docs.ros.org/en/humble/How-To-Guides/Working-with-multiple-RMW-implementations.html))


Aşağıdaki komutla mevcut kullanılan RMW sağlayıcısı öğrenilebilir.
```
echo $RMW_IMPLEMENTATION
```

Aşağıdaki komutla hangi RMW kulanılacağı özelleştirilebilir.
```
export RMW_IMPLEMENTATION=rmw_fastrtps_cpp
```
Bu komutu .bashrc'ye yazarak default olan FAST-DDS'in kullanılması sağlanmalı:
```
echo "export RMW_IMPLEMENTATION=rmw_fastrtps_cpp" >> .bashrc
source ~/.bashrc
```

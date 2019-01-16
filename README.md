# geektime-nginx
极客时间：nginx核心知识100讲配置文件与代码分享

# nginx编译参数
课程截止到第5部分时，用到的模块及编译参数如下：

`
./configure --with-http_auth_request_module --with-http_realip_module --with-http_v2_module --with-debug --add-module=/home/web/nginx-http-concat/ --with-http_random_index_module --with-http_sub_module --with-http_addition_module --with-http_secure_link_module --with-http_geoip_module --with-http_ssl_module --with-stream_ssl_module --with-stream_realip_module --with-stream_ssl_preread_module --with-stream --add-module=/home/web/ngx_cache_purge/ --with-http_slice_module --with-google_perftools_module --with-threads --with-ld-opt=-ltcmalloc --with-http_gzip_static_module --with-http_gunzip_module --with-http_stub_status_module
`

![购买课程](https://img-blog.csdnimg.cn/2019011615093624.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3J1c3NlbGxfdGFv,size_16,color_FFFFFF,t_70)

![架构图](https://img-blog.csdnimg.cn/20190116152033544.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3J1c3NlbGxfdGFv,size_16,color_FFFFFF,t_70)

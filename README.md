# geektime-nginx
极客时间：nginx核心知识100讲配置文件与代码分享

# nginx编译参数
课程截止到第5部分时，用到的模块及编译参数如下：

`
./configure --with-http_auth_request_module --with-http_realip_module --with-http_v2_module --with-debug --add-module=/home/web/nginx-http-concat/ --with-http_random_index_module --with-http_sub_module --with-http_addition_module --with-http_secure_link_module --with-http_geoip_module --with-http_ssl_module --with-stream_ssl_module --with-stream_realip_module --with-stream_ssl_preread_module --with-stream --add-module=/home/web/ngx_cache_purge/ --with-http_slice_module --with-google_perftools_module --with-threads --with-ld-opt=-ltcmalloc --with-http_gzip_static_module --with-http_gunzip_module --with-http_stub_status_module
`


#Configuration of lumberjack

We are using lumberjack to transfer the data.

The nginx patterns are for below log format

log_format info '$remote_addr [$time_local] $status '
                '"$request" $body_bytes_sent "$http_referer" '
                '"$http_user_agent" "$http_x_forwarded_for" '
                '"$upstream_addr" "$upstream_status" "$upstream_cache_status" $upstream_response_time > $request_time';

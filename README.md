# ngx_http_apprentice_module

## example

```

location /test {
    apprentice_string "test";
    apprentice_counter on;
    root html;
    index index.html index.htm;
}

```

# Function: <code>reqsk_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81704c77)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764afc)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff8176e202)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ccf0)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782cac)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81817161)
Location: include/net/request_sock.h:121
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8177ccf0-ffffffff8177cd77: reqsk_put (STB_LOCAL)
ffffffff81817161-ffffffff818171db: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8176b867)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d12b1)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff817dc4a4)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eae75)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f0258)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81890b74)
Location: include/net/request_sock.h:120
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff817eadc0-ffffffff817eae47: reqsk_put (STB_LOCAL)
ffffffff81890b74-ffffffff81890bed: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81798937)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81801171)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff8180c3da)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b7c5)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820c87)
Location: include/net/request_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818c518e)
Location: include/net/request_sock.h:120
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8181b710-ffffffff8181b797: reqsk_put (STB_LOCAL)
ffffffff818c518e-ffffffff818c5207: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff817b6f17)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820eeb)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff8182c633)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183bbf5)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818412bc)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8680)
Location: include/net/request_sock.h:121
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8183bb60-ffffffff8183bbc6: reqsk_put (STB_LOCAL)
ffffffff818b8680-ffffffff818b86e6: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8182f507)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a03bc)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff818ab517)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb5b5)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0a85)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b730)
Location: include/net/request_sock.h:121
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff818bb660-ffffffff818bb6d9: reqsk_put (STB_LOCAL)
ffffffff8193b730-ffffffff8193b7a9: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818799e7)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f5716)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81900944)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191210d)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8191652d)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819950e3)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81911030-ffffffff819110a7: reqsk_put (STB_LOCAL)
ffffffff81994550-ffffffff819945c7: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8189a637)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a56)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff8192ee18)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819408eb)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944ccd)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff819755db)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb9ca)
Location: include/net/request_sock.h:121
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8193f930-ffffffff8193f9a7: reqsk_put (STB_LOCAL)
ffffffff819cae60-ffffffff819caed7: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818e4d12)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985462)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81992002)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4e4c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a93ae)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a473)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819a3e10-ffffffff819a3e8e: reqsk_put (STB_LOCAL)
ffffffff81a398c0-ffffffff81a3993e: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81916ea2)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc77)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff819c8edb)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbb4c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0041)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a71014)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819daa30-ffffffff819daaae: reqsk_put (STB_LOCAL)
ffffffff81a70450-ffffffff81a704ce: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819e9822)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa64b1)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81ab416d)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8cb6)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd231)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a874)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ac66a0-ffffffff81ac6766: reqsk_put (STB_LOCAL)
ffffffff81b68b10-ffffffff81b68bd6: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819e95c2)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0b01)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81abeab6)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4c56)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9241)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv4/syncookies.c (ffffffff81b1533e)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b79348)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ad2570-ffffffff81ad2636: reqsk_put (STB_LOCAL)
ffffffff81b77540-ffffffff81b77606: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819cf6e2)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bbad)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81aaae27)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfced)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac463d)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81b0314e)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67e7a)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81abd270-ffffffff81abd336: reqsk_put (STB_LOCAL)
ffffffff81b66040-ffffffff81b66106: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81a7f222)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b572af)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81b674b7)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d896)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82c7a)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81bc53a6)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2fb05)
Location: include/net/request_sock.h:130
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81b7a700-ffffffff81b7a7c6: reqsk_put (STB_LOCAL)
ffffffff81c2c920-ffffffff81c2c9e6: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81bf34e3)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce522d)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81cf62f8)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d868)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d132c2)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81d5a56e)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccf33)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81d0af60-ffffffff81d0b049: reqsk_put (STB_LOCAL)
ffffffff81dc9c90-ffffffff81dc9d79: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81da1243)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea841d)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81ebad08)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3293)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9232)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81f2499e)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e056)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ed08a0-ffffffff81ed0989: reqsk_put (STB_LOCAL)
ffffffff81f9ac70-ffffffff81f9ad59: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81e0fb13)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06c9d)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81f19199)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31f98)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38327)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81f8452e)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffeac8)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81f2f530-ffffffff81f2f619: reqsk_put (STB_LOCAL)
ffffffff81ffb7d0-ffffffff81ffb8b9: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81ecc5c3)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcafbd)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81fddcfa)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7f90)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe3e7)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff8204aed2)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd826)
Location: include/net/request_sock.h:132
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ff4a80-ffffffff81ff4b69: reqsk_put (STB_LOCAL)
ffffffff820c90d0-ffffffff820c91b9: reqsk_put (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffff800010bb0470)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6dae4)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffff800010c7aa98)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ee60)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93bdc)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39464)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffff800010c8b378-ffff800010c8b408: reqsk_put (STB_LOCAL)
ffff800010d36b38-ffff800010d36bc8: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (c0ccd7dc)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (c0d7c018)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (c0d88318)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c0d9dda4)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (c0da24a8)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (c0e3bf90)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
c0d9c2a4-c0d9c354: reqsk_put (STB_LOCAL)
c0e3a7f4-c0e3a8a4: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (c000000000c85e78)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72f10)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (c000000000d85768)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9da20)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (c000000000da417c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cab8)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
c000000000d9b070-c000000000d9b158: reqsk_put (STB_LOCAL)
c000000000e6a810-c000000000e6a8f8: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffe0007412b2)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d5c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffe0007de72e)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef028)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f323c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876660)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818b6ea2)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bae7)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81968d4b)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b9bc)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197feb1)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a106a4)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8197a8a0-ffffffff8197a91e: reqsk_put (STB_LOCAL)
ffffffff81a0fae0-ffffffff81a0fb5e: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81870df2)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819155d7)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff8192283b)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193547c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939971)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd464)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81934360-ffffffff819343de: reqsk_put (STB_LOCAL)
ffffffff819cc8a0-ffffffff819cc91e: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81907ea2)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c62b7)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff819d351b)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e618c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea681)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b124)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819e5070-ffffffff819e50ee: reqsk_put (STB_LOCAL)
ffffffff81a7a560-ffffffff81a7a5de: reqsk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_put(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81928ee2)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfd9d)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff819dd0c2)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efe4c)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f44e0)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87964)
Location: include/net/request_sock.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819eed20-ffffffff819eed9e: reqsk_put (STB_LOCAL)
ffffffff81a86da0-ffffffff81a86e1e: reqsk_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

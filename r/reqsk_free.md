# Function: <code>reqsk_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_free(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81704c89)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff817627b2)
Location: include/net/request_sock.h:109
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764b10)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff8176e079)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ccff)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782dd8)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff817ab110)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81817170)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:reqsk_put
```
```
In net/ipv6/syncookies.c (ffffffff817ff7bc)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817ab110-ffffffff817ab18d: reqsk_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_free(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8176b870)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce5bf)
Location: include/net/request_sock.h:108
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d12b1)
Location: include/net/request_sock.h:108
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
In net/ipv4/tcp_input.c (ffffffff817dc261)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eae81)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f0265)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81818dd9)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81890b82)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:reqsk_put
```
```
In net/ipv6/syncookies.c (ffffffff8186f12b)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81818c00-ffffffff81818c7d: reqsk_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_free(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81798940)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe3cf)
Location: include/net/request_sock.h:108
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81801171)
Location: include/net/request_sock.h:108
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
In net/ipv4/tcp_input.c (ffffffff8180c3cb)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b7d1)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820c94)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff8184a639)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818c519c)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:reqsk_put
```
```
In net/ipv6/syncookies.c (ffffffff818a2096)
Location: include/net/request_sock.h:108
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8184a460-ffffffff8184a4dd: reqsk_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_free(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff817b6f20)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e7a7)
Location: include/net/request_sock.h:109
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820eeb)
Location: include/net/request_sock.h:109
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
In net/ipv4/tcp_input.c (ffffffff8182c641)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183bc31)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818412c9)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff8186dfcf)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8690)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:reqsk_put
```
```
In net/ipv6/syncookies.c (ffffffff818c8721)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8186de20-ffffffff8186de7e: reqsk_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_free(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8182f516)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189d97b)
Location: include/net/request_sock.h:109
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a03cf)
Location: include/net/request_sock.h:109
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
In net/ipv4/tcp_input.c (ffffffff818ab52b)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb5f7)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0a98)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff818ee949)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
Direct callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b747)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:reqsk_put
```
```
In net/ipv6/syncookies.c (ffffffff8194bce6)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818ee770-ffffffff818ee7da: reqsk_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818799f6)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f17d4)
Location: include/net/request_sock.h:109
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f585e)
Location: include/net/request_sock.h:109
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
In net/ipv4/tcp_input.c (ffffffff81900958)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819121d5)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916540)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff819459b5)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819951ab)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff819a4f42)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8189a646)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f334)
Location: include/net/request_sock.h:109
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922b9e)
Location: include/net/request_sock.h:109
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
In net/ipv4/tcp_input.c (ffffffff8192e9e0)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819409b2)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944ce0)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81975d2f)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cba91)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff819dba27)
Location: include/net/request_sock.h:109
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818e4d23)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81981c77)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985477)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81992016)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4f26)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a93c1)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff819df8a1)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a545)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a4a6c9)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81916eb3)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b84c7)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc8c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff819c8eef)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbc26)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0054)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81a16901)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a710e6)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a8129d)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819e9855)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa309d)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6658)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81ab455a)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8dd5)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd28c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv4/syncookies.c (ffffffff81b07924)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a98a)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81b7bf3a)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819e95f5)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad5cd)
Location: include/net/request_sock.h:124
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0ca8)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81abeeea)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4d75)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad929c)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv4/syncookies.c (ffffffff81b15cea)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b79458)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81b8af6b)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819cf715)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9869d)
Location: include/net/request_sock.h:124
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bd54)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81aab31e)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfe1c)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac46eb)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81b03af1)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67fa1)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81b79dce)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81a7f255)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53b7d)
Location: include/net/request_sock.h:124
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57457)
Location: include/net/request_sock.h:124
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
In net/ipv4/tcp_input.c (ffffffff81b672a4)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d9ec)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82df5)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81bc5d9e)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2fc48)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81c44a86)
Location: include/net/request_sock.h:124
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81bf3513)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1674)
Location: include/net/request_sock.h:126
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce53df)
Location: include/net/request_sock.h:126
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
In net/ipv4/tcp_input.c (ffffffff81cf67c1)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d9c5)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d13405)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81d5b032)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd053)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81de3a87)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81da1273)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea27f4)
Location: include/net/request_sock.h:126
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea85cf)
Location: include/net/request_sock.h:126
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
In net/ipv4/tcp_input.c (ffffffff81ebb1d1)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3384)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9375)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81f254a2)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e13e)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81fb6107)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81e0fb43)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01014)
Location: include/net/request_sock.h:126
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06e4f)
Location: include/net/request_sock.h:126
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
In net/ipv4/tcp_input.c (ffffffff81f1965c)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f32089)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f3845a)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81f85032)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffebae)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff8201681f)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81ecc5f3)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5374)
Location: include/net/request_sock.h:126
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb16f)
Location: include/net/request_sock.h:126
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
In net/ipv4/tcp_input.c (ffffffff81fdd9dc)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff8080)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe51a)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff8204b74d)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd91d)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff820e584b)
Location: include/net/request_sock.h:126
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffff800010bb0480)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6999c)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6db78)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffff800010c7aaa8)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ef48)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93bf4)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffff800010cd251c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39540)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffff800010d4ca08)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (c0ccd7ec)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (c0d78ac0)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7c158)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (c0d88328)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c0d9de74)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (c0da24b8)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (c0ddc410)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (c0e3c05c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (c0e4dcfc)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (c000000000c85ea0)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e780)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73100)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (c000000000d8550c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9db8c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (c000000000da41a4)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (c000000000df0a3c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cbf8)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (c000000000e831d0)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void reqsk_free(struct request_sock *req);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffe0007412c4)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf75a)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2ebe)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffe0007de740)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ede74)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_req_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f324e)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffe0008238a0)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873b72)
Location: include/net/request_sock.h:117
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffe00088577c)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe0007ead52-ffffffe0007eadb4: reqsk_free (STB_LOCAL)
ffffffe000873b72-ffffffe000873bd4: reqsk_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818b6eb3)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958337)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bafc)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff81968d5f)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197ba96)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197fec4)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff819b5f91)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10776)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a2092d)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81870e03)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81911e27)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819155ec)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff8192284f)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81935556)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939984)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81972d81)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd536)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff819dd6ed)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81907eb3)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2b07)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c62cc)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff819d352f)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e6266)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea694)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81a20831)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b1f6)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a8b3ad)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81928ef3)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc507)
Location: include/net/request_sock.h:117
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfde8)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_input.c (ffffffff819dd0d6)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eff26)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4500)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/syncookies.c (ffffffff81a2bd31)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87a36)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a97fc1)
Location: include/net/request_sock.h:117
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
</ul>
<b>Arch</b>
<ul>
</ul>

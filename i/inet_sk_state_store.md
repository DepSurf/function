# Function: <code>inet_sk_state_store</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8192b530)
Location: net/ipv4/af_inet.c:1285
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff8192b530-ffffffff8192b5cb: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8195a9c0)
Location: net/ipv4/af_inet.c:1285
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff8195a9c0-ffffffff8195aa5b: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bf5b0)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff819bf5b0-ffffffff819bf64d: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f61f0)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff819f61f0-ffffffff819f628d: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae46f0)
Location: net/ipv4/af_inet.c:1323
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_socket_create
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
```
**Symbols:**

```
ffffffff81ae46f0-ffffffff81ae476c: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af1650)
Location: net/ipv4/af_inet.c:1321
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_check_fastclose
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
```
**Symbols:**

```
ffffffff81af1650-ffffffff81af16aa: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adce40)
Location: net/ipv4/af_inet.c:1325
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
**Symbols:**

```
ffffffff81adce40-ffffffff81adce9a: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b9c230)
Location: net/ipv4/af_inet.c:1327
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
**Symbols:**

```
ffffffff81b9c230-ffffffff81b9c287: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2e180)
Location: net/ipv4/af_inet.c:1322
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
**Symbols:**

```
ffffffff81d2e180-ffffffff81d2e1f3: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef60d0)
Location: net/ipv4/af_inet.c:1342
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
**Symbols:**

```
ffffffff81ef60d0-ffffffff81ef6143: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f55b30)
Location: net/ipv4/af_inet.c:1341
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:mptcp_set_connected
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81f55b30-ffffffff81f55ba3: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201c010)
Location: net/ipv4/af_inet.c:1361
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_error_report
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff8201c010-ffffffff8201c083: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cacad8)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffff800010cacad8-ffff800010cacbbc: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db9090)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
c0db9090-c0db9180: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc2b40)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
c000000000dc2b40-c000000000dc2c60: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe0008069ec)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffe0008069ec-ffffffe000806a8c: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81995f90)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff81995f90-ffffffff8199602d: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194fa50)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff8194fa50-ffffffff8194faed: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a00830)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff81a00830-ffffffff81a008cd: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock *sk, int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a0acf0)
Location: net/ipv4/af_inet.c:1291
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/tcp.c:tcp_set_state
```
**Symbols:**

```
ffffffff81a0acf0-ffffffff81a0ada2: inet_sk_state_store (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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

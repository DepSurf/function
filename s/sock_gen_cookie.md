# Function: <code>sock_gen_cookie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81732f10)
Location: net/core/sock_diag.c:22
Inline: False
Direct callers:
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
```
**Symbols:**

```
ffffffff81732f10-ffffffff81732f52: sock_gen_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff8179e930)
Location: net/core/sock_diag.c:22
Inline: False
Direct callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
**Symbols:**

```
ffffffff8179e930-ffffffff8179e972: sock_gen_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff817cd300)
Location: net/core/sock_diag.c:22
Inline: False
Direct callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
**Symbols:**

```
ffffffff817cd300-ffffffff817cd342: sock_gen_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff817ecdf0)
Location: net/core/sock_diag.c:22
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
**Symbols:**

```
ffffffff817ecdf0-ffffffff817ece32: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81868fe0)
Location: net/core/sock_diag.c:22
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
**Symbols:**

```
ffffffff81868fe0-ffffffff81869024: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff818b8e60)
Location: net/core/sock_diag.c:23
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff818b8e60-ffffffff818b8ea3: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff818dfab0)
Location: net/core/sock_diag.c:23
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff818dfab0-ffffffff818dfaf3: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff8192e100)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff8192e100-ffffffff8192e141: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81960390)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff81960390-ffffffff819603d1: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81a338f0)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff81a338f0-ffffffff81a33931: sock_gen_cookie (STB_GLOBAL)
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
In net/core/sock.c (ffffffff819e7773)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/sock_diag.c (ffffffff81a35d35)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/net-traces.c (ffffffff81a48134)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
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
In net/core/sock.c (ffffffff819cd184)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/filter.c (ffffffff81a1194a)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
```
```
In net/core/sock_diag.c (ffffffff81a1ce95)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/net-traces.c (ffffffff81a2d08f)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/bpf/test_run.c (ffffffff81a723fd)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
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
In net/core/sock.c (ffffffff81a7ca73)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/filter.c (ffffffff81ac2e5a)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
```
```
In net/core/sock_diag.c (ffffffff81ad0715)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/net-traces.c (ffffffff81ae2675)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/bpf/test_run.c (ffffffff81b2bd59)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
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
In net/core/sock.c (ffffffff81bf3271)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/filter.c (ffffffff81c3db1c)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
```
```
In net/core/sock_diag.c (ffffffff81c4dfc5)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/net-traces.c (ffffffff81c6623d)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/bpf/test_run.c (ffffffff81cb6316)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
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
In net/core/sock.c (ffffffff81da0843)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/filter.c (ffffffff81df1a5c)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
```
```
In net/core/sock_diag.c (ffffffff81e02fd5)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/net-traces.c (ffffffff81e1cf9a)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/bpf/test_run.c (ffffffff81e747eb)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
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
In net/core/sock.c (ffffffff81e0ecb7)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/filter.c (ffffffff81e639ec)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
```
```
In net/core/sock_diag.c (ffffffff81e75575)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/net-traces.c (ffffffff81e9189a)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/bpf/test_run.c (ffffffff81ed05c1)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
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
In net/core/sock.c (ffffffff81ecb790)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/filter.c (ffffffff81f22bcc)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
```
```
In net/core/sock_diag.c (ffffffff81f34e25)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/net-traces.c (ffffffff81f53c5a)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/bpf/test_run.c (ffffffff81f93f21)
Location: include/linux/sock_diag.h:30
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
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
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffff800010c03c10)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffff800010c03c10-ffff800010c03ca4: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (c0d1cf70)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
c0d1cf70-c0d1d014: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (c000000000ced610)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
c000000000ced610-c000000000ced694: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffe00078253c)
Location: net/core/sock_diag.c:24
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffe000782c7a-ffffffe000782cc6: sock_gen_cookie (STB_GLOBAL)
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
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81900360)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff81900360-ffffffff819003a1: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff818ba190)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff818ba190-ffffffff818ba1d1: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81951390)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff81951390-ffffffff819513d1: sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81972d80)
Location: net/core/sock_diag.c:24
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
**Symbols:**

```
ffffffff81972d80-ffffffff81972dc1: sock_gen_cookie (STB_GLOBAL)
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

# Function: <code>__sock_gen_cookie</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 __sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81a35c60)
Location: net/core/sock_diag.c:25
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
ffffffff81a35c60-ffffffff81a35cf0: __sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 __sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81a1cdb0)
Location: net/core/sock_diag.c:25
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:bpf_get_socket_cookie_sock
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff81a1cdb0-ffffffff81a1ce43: __sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 __sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81ad0630)
Location: net/core/sock_diag.c:25
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:bpf_get_socket_cookie_sock
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff81ad0630-ffffffff81ad06c3: __sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 __sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_diag.c (ffffffff81c4dec0)
Location: net/core/sock_diag.c:26
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:bpf_get_socket_cookie_sock
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff81c4dec0-ffffffff81c4df58: __sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 __sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_diag.c (ffffffff81e02fe4)
Location: net/core/sock_diag.c:26
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sk_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:bpf_get_socket_cookie_sock
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff81e02d20-ffffffff81e02d99: __sock_gen_cookie.part.0 (STB_LOCAL)
ffffffff81e03040-ffffffff81e03066: __sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 __sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_diag.c (ffffffff81e75584)
Location: net/core/sock_diag.c:26
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sk_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:bpf_get_socket_cookie_sock
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff81e752a0-ffffffff81e75319: __sock_gen_cookie.part.0 (STB_LOCAL)
ffffffff81e755e0-ffffffff81e75606: __sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 __sock_gen_cookie(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_diag.c (ffffffff81f34e34)
Location: net/core/sock_diag.c:26
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem
  - net/core/sock.c:sk_getsockopt
  - net/core/filter.c:bpf_get_socket_cookie_sock_ops
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:bpf_get_socket_cookie_sock
  - net/core/filter.c:bpf_get_socket_cookie_sock_addr
  - net/core/filter.c:bpf_get_socket_cookie
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff81f34b40-ffffffff81f34bb9: __sock_gen_cookie.part.0 (STB_LOCAL)
ffffffff81f34e90-ffffffff81f34eb6: __sock_gen_cookie (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

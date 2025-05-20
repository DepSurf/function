# Function: <code>__cgroup_bpf_run_filter_sock_addr</code>

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
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d19c0)
Location: kernel/bpf/cgroup.c:563
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff811d19c0-ffffffff811d1ac5: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e16c0)
Location: kernel/bpf/cgroup.c:620
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff811e16c0-ffffffff811e17ed: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f77b0)
Location: kernel/bpf/cgroup.c:693
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff811f77b0-ffffffff811f792d: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204750)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81204750-ffffffff812048cd: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122c360)
Location: kernel/bpf/cgroup.c:1040
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8122c360-ffffffff8122c4dd: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234770)
Location: kernel/bpf/cgroup.c:1064
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81234770-ffffffff8123490c: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx, u32 *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81239410)
Location: kernel/bpf/cgroup.c:1066
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_pre_connect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_pre_connect
```
**Symbols:**

```
ffffffff81239410-ffffffff81239679: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum cgroup_bpf_attach_type atype, void *t_ctx, u32 *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812734c0)
Location: kernel/bpf/cgroup.c:1096
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_pre_connect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_pre_connect
```
**Symbols:**

```
ffffffff812734c0-ffffffff81273694: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum cgroup_bpf_attach_type atype, void *t_ctx, u32 *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c2e10)
Location: kernel/bpf/cgroup.c:1248
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff812c2e10-ffffffff812c3021: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum cgroup_bpf_attach_type atype, void *t_ctx, u32 *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813275d0)
Location: kernel/bpf/cgroup.c:1462
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff813275d0-ffffffff813277e1: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum cgroup_bpf_attach_type atype, void *t_ctx, u32 *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81357910)
Location: kernel/bpf/cgroup.c:1462
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81357910-ffffffff81357b27: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, int *uaddrlen, enum cgroup_bpf_attach_type atype, void *t_ctx, u32 *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81380440)
Location: kernel/bpf/cgroup.c:1466
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_pre_connect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_bind_sk
  - net/ipv4/ping.c:ping_pre_connect
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind_sk
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_pre_connect
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_pre_connect
  - net/ipv6/ping.c:ping_v6_pre_connect
```
**Symbols:**

```
ffffffff81380440-ffffffff813806aa: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028de48)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffff80001028de48-ffff80001028e00c: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bc864)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c04bc864-c04bca84: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033a7c0)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c00000000033a7c0-c00000000033aa14: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c0718)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffe0001c0718-ffffffe0001c08b2: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fcd70)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff811fcd70-ffffffff811fceed: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811efac0)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff811efac0-ffffffff811efc3d: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fab40)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff811fab40-ffffffff811facbd: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_addr(struct sock *sk, struct sockaddr *uaddr, enum bpf_attach_type type, void *t_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209580)
Location: kernel/bpf/cgroup.c:703
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81209580-ffffffff81209734: __cgroup_bpf_run_filter_sock_addr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *uaddrlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, uaddr, atype, t_ctx, flags</code> ➡️ <code>sk, uaddr, uaddrlen, atype, t_ctx, flags</code>
</li>
</ul>
</details>
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

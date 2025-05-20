# Function: <code>sock_kmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700a20)
Location: net/core/sock.c:1763
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/exthdrs.c:ipv6_dup_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81700a20-ffffffff81700a72: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817673e0)
Location: net/core/sock.c:1792
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff817673e0-ffffffff81767434: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794400)
Location: net/core/sock.c:1790
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff81794400-ffffffff81794454: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b27f0)
Location: net/core/sock.c:1929
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff817b27f0-ffffffff817b2844: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182aa00)
Location: net/core/sock.c:1967
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff8182aa00-ffffffff8182aa54: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818758d0)
Location: net/core/sock.c:1987
Inline: True
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff818758d0-ffffffff81875926: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81896210)
Location: net/core/sock.c:1983
Inline: True
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff81896210-ffffffff81896266: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e2360)
Location: net/core/sock.c:2124
Inline: True
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff818e2360-ffffffff818e23af: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914510)
Location: net/core/sock.c:2139
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff81914510-ffffffff8191455f: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4720)
Location: net/core/sock.c:2248
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff819e4720-ffffffff819e476f: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff819e3f90)
Location: net/core/sock.c:2240
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff819e3f90-ffffffff819e3fc7: sock_kmalloc.part.0 (STB_LOCAL)
ffffffff819e3fd0-ffffffff819e3ffc: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff819ca020)
Location: net/core/sock.c:2263
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff819ca020-ffffffff819ca057: sock_kmalloc.part.0 (STB_LOCAL)
ffffffff819ca060-ffffffff819ca08c: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff81a79560)
Location: net/core/sock.c:2387
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff81a79560-ffffffff81a79597: sock_kmalloc.part.0 (STB_LOCAL)
ffffffff81a795a0-ffffffff81a795cc: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bec240)
Location: net/core/sock.c:2554
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
**Symbols:**

```
ffffffff81bec240-ffffffff81bec2aa: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d98c80)
Location: net/core/sock.c:2633
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
**Symbols:**

```
ffffffff81d98c80-ffffffff81d98cf9: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e07020)
Location: net/core/sock.c:2693
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
**Symbols:**

```
ffffffff81e07020-ffffffff81e0707b: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec3880)
Location: net/core/sock.c:2673
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
  - net/mptcp/protocol.c:mptcp_copy_ip_options
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
**Symbols:**

```
ffffffff81ec3880-ffffffff81ec38e2: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bac230)
Location: net/core/sock.c:2139
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffff800010bac230-ffff800010bac2ec: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccae4c)
Location: net/core/sock.c:2139
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
c0ccae4c-c0ccaee0: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c82960)
Location: net/core/sock.c:2139
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
c000000000c82960-c000000000c82a48: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073dbe8)
Location: net/core/sock.c:2139
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffe00073dbe8-ffffffe00073dc52: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4510)
Location: net/core/sock.c:2139
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff818b4510-ffffffff818b455f: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186e460)
Location: net/core/sock.c:2139
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff8186e460-ffffffff8186e4af: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905510)
Location: net/core/sock.c:2139
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff81905510-ffffffff8190555f: sock_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *sock_kmalloc(struct sock *sk, int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926520)
Location: net/core/sock.c:2139
Inline: True
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
**Symbols:**

```
ffffffff81926520-ffffffff8192656f: sock_kmalloc (STB_GLOBAL)
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

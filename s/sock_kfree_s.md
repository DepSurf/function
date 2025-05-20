# Function: <code>sock_kfree_s</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81702820)
Location: net/core/sock.c:1797
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81702820-ffffffff8170286f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817696d0)
Location: net/core/sock.c:1826
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff817696d0-ffffffff8176971f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794740)
Location: net/core/sock.c:1824
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81794740-ffffffff8179478f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b49e0)
Location: net/core/sock.c:1963
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff817b49e0-ffffffff817b4a0f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182cf90)
Location: net/core/sock.c:2001
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff8182cf90-ffffffff8182cfc3: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874c90)
Location: net/core/sock.c:2021
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81874c90-ffffffff81874cc0: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895550)
Location: net/core/sock.c:2017
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81895550-ffffffff81895580: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1bd0)
Location: net/core/sock.c:2158
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff818e1bd0-ffffffff818e1bff: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913750)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81913750-ffffffff8191377f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4f20)
Location: net/core/sock.c:2282
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819e4f20-ffffffff819e4f4f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e47f0)
Location: net/core/sock.c:2274
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819e47f0-ffffffff819e481f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c9630)
Location: net/core/sock.c:2297
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819c9630-ffffffff819c965f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79df0)
Location: net/core/sock.c:2421
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a79df0-ffffffff81a79e1f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bedad0)
Location: net/core/sock.c:2590
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
**Symbols:**

```
ffffffff81bedad0-ffffffff81bedb13: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d98e50)
Location: net/core/sock.c:2669
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
**Symbols:**

```
ffffffff81d98e50-ffffffff81d98e93: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e086b0)
Location: net/core/sock.c:2729
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
**Symbols:**

```
ffffffff81e086b0-ffffffff81e086f3: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec3a40)
Location: net/core/sock.c:2709
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
**Symbols:**

```
ffffffff81ec3a40-ffffffff81ec3a83: sock_kfree_s (STB_GLOBAL)
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
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bab6b8)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffff800010bab6b8-ffff800010bab73c: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9f04)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
c0cc9f04-c0cc9f84: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c815d0)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
c000000000c815d0-c000000000c81648: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073cc48)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffe00073cc48-ffffffe00073cc9e: sock_kfree_s (STB_GLOBAL)
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
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3750)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff818b3750-ffffffff818b377f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186d6a0)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff8186d6a0-ffffffff8186d6cf: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904750)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81904750-ffffffff8190477f: sock_kfree_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_kfree_s(struct sock *sk, void *mem, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819257f0)
Location: net/core/sock.c:2173
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819257f0-ffffffff8192581f: sock_kfree_s (STB_GLOBAL)
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

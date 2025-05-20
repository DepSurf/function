# Function: <code>copy_to_sockptr_offset</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f9f1)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e5a1)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
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
In kernel/bpf/verifier.c (ffffffff8123b1a4)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_line
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c365d3)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
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
In kernel/bpf/verifier.c (ffffffff81280d2f)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd407e)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int copy_to_sockptr_offset(sockptr_t dst, size_t offset, const void *src, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d09b0)
Location: include/linux/sockptr.h:58
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In security/selinux/hooks.c (ffffffff81674c2a)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (ffffffff8169c69b)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/apparmor/lsm.c (ffffffff816da026)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In net/core/sock.c (ffffffff81da094c)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/filter.c (ffffffff81e023da)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1cac)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
```
```
In net/ipv4/tcp.c (ffffffff81eb42c6)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/igmp.c (ffffffff81efc08b)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/ipmr.c (ffffffff81f2216a)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f816c1)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/mcast.c (ffffffff81f91fb0)
Location: include/linux/sockptr.h:58
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4570)
Location: include/linux/sockptr.h:58
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
```
In net/ipv6/ip6mr.c (ffffffff81fb00ff)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
**Symbols:**

```
ffffffff812d09b0-ffffffff812d09ea: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81eaba50-ffffffff81eabacc: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81f7e9e0-ffffffff81f7ea66: copy_to_sockptr_offset (STB_LOCAL)
ffffffff81f91fb0-ffffffff81f92068: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81fa4570-ffffffff81fa45ac: copy_to_sockptr_offset.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int copy_to_sockptr_offset(sockptr_t dst, size_t offset, const void *src, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fb030)
Location: include/linux/sockptr.h:58
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/btf.c (ffffffff8133a1b0)
Location: include/linux/sockptr.h:58
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
```
```
In security/selinux/hooks.c (ffffffff816ad5ac)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (ffffffff816d551b)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/apparmor/lsm.c (ffffffff81713d37)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In net/core/sock.c (ffffffff81e0e9b2)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/filter.c (ffffffff81e7478a)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f00247)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
```
```
In net/ipv4/tcp.c (ffffffff81f12444)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/igmp.c (ffffffff81f5babb)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/ipmr.c (ffffffff81f81d1a)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1d91)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/mcast.c (ffffffff81ff28e0)
Location: include/linux/sockptr.h:58
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82004e20)
Location: include/linux/sockptr.h:58
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
```
In net/ipv6/ip6mr.c (ffffffff8201080f)
Location: include/linux/sockptr.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
**Symbols:**

```
ffffffff812fb030-ffffffff812fb06a: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff8133a1b0-ffffffff8133a1ea: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81f0a210-ffffffff81f0a28c: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81fdebf0-ffffffff81fdec76: copy_to_sockptr_offset (STB_LOCAL)
ffffffff81ff28e0-ffffffff81ff2998: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff82004e20-ffffffff82004e5c: copy_to_sockptr_offset.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int copy_to_sockptr_offset(sockptr_t dst, size_t offset, const void *src, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131ae40)
Location: include/linux/sockptr.h:81
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/btf.c (ffffffff813602e0)
Location: include/linux/sockptr.h:81
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/cgroup.c (ffffffff81383fa9)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
```
```
In security/selinux/hooks.c (ffffffff816ea63c)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (ffffffff81711d4b)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/apparmor/lsm.c (ffffffff81751bca)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In net/core/sock.c (ffffffff81ecbee0)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/filter.c (ffffffff81f33f4a)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc4711)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
```
```
In net/ipv4/tcp.c (ffffffff81fd6a0c)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
```
In net/ipv4/igmp.c (ffffffff82021ffb)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/ipmr.c (ffffffff8204839a)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/ipv4/tcp_ao.c (ffffffff820599ad)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820afcac)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/mcast.c (ffffffff820c0550)
Location: include/linux/sockptr.h:81
Inline: True
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d3bf0)
Location: include/linux/sockptr.h:81
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
```
In net/ipv6/ip6mr.c (ffffffff820df79f)
Location: include/linux/sockptr.h:81
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
**Symbols:**

```
ffffffff8131ae40-ffffffff8131ae7a: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff813602e0-ffffffff8136031a: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff81fce320-ffffffff81fce39c: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff820ac770-ffffffff820ac7f6: copy_to_sockptr_offset (STB_LOCAL)
ffffffff820c0550-ffffffff820c0608: copy_to_sockptr_offset.constprop.0 (STB_LOCAL)
ffffffff820d3bf0-ffffffff820d3c2c: copy_to_sockptr_offset.constprop.0.isra.0 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

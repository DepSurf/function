# Function: <code>skb_to_full_sk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813492f3)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_postroute
```
```
In security/selinux/netlabel.c (ffffffff8135d58d)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8136616d)
Location: include/net/inet_sock.h:239
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137e5bc)
Location: include/net/inet_sock.h:258
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8139356b)
Location: include/net/inet_sock.h:258
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8139c24d)
Location: include/net/inet_sock.h:258
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
```
```
In net/core/filter.c (ffffffff8179cce1)
Location: include/net/inet_sock.h:258
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8139504c)
Location: include/net/inet_sock.h:259
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff813aa18b)
Location: include/net/inet_sock.h:259
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff813b2dfd)
Location: include/net/inet_sock.h:259
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
```
```
In net/core/filter.c (ffffffff817c9604)
Location: include/net/inet_sock.h:259
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ab0e6)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff813c0b6b)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff813c978d)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/filter.c (ffffffff817e8544)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff8186e7dd)
Location: include/net/inet_sock.h:263
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813d1146)
Location: include/net/inet_sock.h:267
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff813e6d3b)
Location: include/net/inet_sock.h:267
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff813efc1d)
Location: include/net/inet_sock.h:267
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81849cd8)
Location: include/net/inet_sock.h:267
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818638a4)
Location: include/net/inet_sock.h:267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff818ef19d)
Location: include/net/inet_sock.h:267
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff813fe3b0)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff81417b3d)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81420a4a)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81893ed4)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818aea3a)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff81945b41)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff8141a240)
Location: include/net/inet_sock.h:284
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8143406d)
Location: include/net/inet_sock.h:284
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8143d09a)
Location: include/net/inet_sock.h:284
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff818b48c4)
Location: include/net/inet_sock.h:284
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818d2d3a)
Location: include/net/inet_sock.h:284
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff81975e61)
Location: include/net/inet_sock.h:284
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff81447cc9)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff81461b21)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8146ac9a)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff819011f7)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8191fe2a)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff819df9f0)
Location: include/net/inet_sock.h:280
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff81461859)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8147b8d1)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81484a7a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81933527)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8195206a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff81a16a20)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff814b4de0)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (0)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814dab65)
Location: include/net/inet_sock.h:281
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff815000ff)
Location: include/net/inet_sock.h:281
Inline: True
```
```
In net/core/dev.c (ffffffff81a0838b)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a23265)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff81b07a60)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff814d2a71)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (0)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814f7fe5)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff8151d2af)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In net/core/dev.c (ffffffff81a0991a)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a27f45)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
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
In security/selinux/hooks.c (ffffffff814d8fd1)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (0)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814fed45)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81523abf)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In net/core/dev.c (ffffffff819f0291)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a0f2b5)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
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
In security/selinux/hooks.c (ffffffff815320cd)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (0)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81559d95)
Location: include/net/inet_sock.h:281
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81581d4f)
Location: include/net/inet_sock.h:281
Inline: True
```
```
In net/core/dev.c (ffffffff81aa16c1)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81acbf15)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
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
In security/selinux/hooks.c (ffffffff815c94bc)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff815e8e7c)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff815f4a85)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff81620b3f)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81c196ff)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81c48935)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
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
In security/selinux/hooks.c (ffffffff816766ac)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8169874c)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff816a5525)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff816d426f)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81dca73f)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81dfd6b5)
Location: include/net/inet_sock.h:299
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
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
In security/selinux/hooks.c (ffffffff816ae9cc)
Location: include/net/inet_sock.h:304
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff816d0bcd)
Location: include/net/inet_sock.h:304
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff816ddf05)
Location: include/net/inet_sock.h:304
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff8170d1ff)
Location: include/net/inet_sock.h:304
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81e3b2bf)
Location: include/net/inet_sock.h:304
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81e6dfa5)
Location: include/net/inet_sock.h:304
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
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
In security/selinux/hooks.c (ffffffff816eba0d)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8170d22a)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8171aae5)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
```
```
In security/apparmor/lsm.c (ffffffff8174b6b1)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
```
```
In net/core/dev.c (ffffffff81ef9679)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f2d495)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff81fbbd49)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff82085c1a)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In security/selinux/hooks.c (ffff80001054efc8)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffff80001056c384)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffff800010576ec4)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffff800010bd162c)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffff800010bf4238)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffff800010cd2678)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (c0708994)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (c071fbd8)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (c0729cb8)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (c0cec264)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c0d0ca10)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (c0ddc580)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (c0000000006b0274)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (c0000000006d055c)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (c0000000006e0384)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (c000000000caf9c8)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c000000000cd9394)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (c000000000df0c50)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffe0003a8f48)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffe0003c0e98)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffe0003c9446)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffe00075baf4)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffe0007756f6)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffe0008239c2)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff81459e39)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff81473eb1)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8147d05a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff818d3527)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818f203a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff819b60b0)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff8144a869)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff814648d1)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff8146da7a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff8188d3b7)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818abe6a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff81972ea0)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff81455ed9)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff8146ff51)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff814790fa)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff81924527)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8194306a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff81a20950)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In security/selinux/hooks.c (ffffffff814711c9)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
```
```
In security/selinux/netlabel.c (ffffffff814877c1)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
```
```
In security/smack/smack_netfilter.c (ffffffff81490baa)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
```
In net/core/dev.c (ffffffff819459b7)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8196495a)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/netfilter.c (ffffffff81a2be70)
Location: include/net/inet_sock.h:281
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
</details>
</li>
</ul>

## Differences

# Function: <code>l3mdev_master_dev_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183bb58)
Location: include/net/l3mdev.h:83
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
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
In net/ipv4/route.c (ffffffff817f1124)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/ipmr.c (ffffffff8184896d)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_forward
```
```
In net/ipv6/addrconf.c (ffffffff8186d558)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81878bac)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
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
In net/ipv4/route.c (ffffffff81812818)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv6/addrconf.c (ffffffff8189239d)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff8189de78)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
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
In net/ipv4/route.c (ffffffff81891e3a)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv6/addrconf.c (ffffffff8190f6c7)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81918ea9)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/ipv4/route.c (ffffffff818e60fa)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81966b0c)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81970be7)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/ipv4/route.c (ffffffff81913012)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff8199c12c)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff819a6817)
Location: include/net/l3mdev.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff819430b9)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819755e2)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81a07f42)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81a12ee1)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81978069)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819abffe)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81a3eab5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81a49ad1)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81a4cb87)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a95f3e)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81b34035)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81b404a3)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81a52847)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a9ffbf)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81b42bd5)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81b4ef63)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81a38017)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81a8aeff)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81b30b65)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81b3cda3)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81aede57)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81b45e3f)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81bf7085)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81c03743)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81c70c84)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81cd2be3)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81d9034d)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81d9d765)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81e28d04)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81e92eb3)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81f5e90d)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81f6c725)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81e9e334)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81ef1653)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81fbe5ed)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81fcc865)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81f60ab4)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff81fb57a3)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff8208ba7d)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff8209a03d)
Location: include/net/l3mdev.h:95
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffff800010c1e910)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffff800010c5c12c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffff800010cff938)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffff800010d0cc3c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (c0d36944)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (c0d6b7ac)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (c0e07eb4)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (c0e1343c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (c000000000d10a30)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (c000000000d5e45c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (c000000000e295d0)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (c000000000e382b0)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffe00079855a)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffe0007c5196)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffe00084a21a)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffe000854252)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81917ed9)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff8194be6e)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff819de145)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff819e9161)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff818d1c89)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff8190595e)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff8199af05)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff819a5f21)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff81969069)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819b663e)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81a48bc5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81a53be1)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
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
In net/core/lwt_bpf.c (ffffffff8198b449)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/route.c (ffffffff819bfe75)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/addrconf.c (ffffffff81a54d3d)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
```
```
In net/ipv6/route.c (ffffffff81a5fbd1)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
</details>
</li>
</ul>

## Differences

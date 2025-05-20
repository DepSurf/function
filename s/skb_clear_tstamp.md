# Function: <code>skb_clear_tstamp</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:4241
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81a519d1)
Location: include/linux/skbuff.h:4241
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/skbuff.c (ffffffff81bf631a)
Location: include/linux/skbuff.h:4241
Inline: True
```
```
In net/core/filter.c (ffffffff81c43e4c)
Location: include/linux/skbuff.h:4241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/ip_forward.c (ffffffff81cd710b)
Location: include/linux/skbuff.h:4241
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b924)
Location: include/linux/skbuff.h:4241
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:4137
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81bdac11)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/skbuff.c (ffffffff81da4c0a)
Location: include/linux/skbuff.h:4137
Inline: True
```
```
In net/core/filter.c (ffffffff81df819c)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/ip_forward.c (ffffffff81e976cb)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv6/ip6_output.c (ffffffff81f5992e)
Location: include/linux/skbuff.h:4137
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:4169
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81c316b5)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/skbuff.c (ffffffff81e13894)
Location: include/linux/skbuff.h:4169
Inline: True
```
```
In net/core/filter.c (ffffffff81e6980e)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/ip_forward.c (ffffffff81ef5efb)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv6/ip6_output.c (ffffffff81fb95e2)
Location: include/linux/skbuff.h:4169
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:4206
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81ce4535)
Location: include/linux/skbuff.h:4206
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/core/skbuff.c (ffffffff81ed08c4)
Location: include/linux/skbuff.h:4206
Inline: True
```
```
In net/core/filter.c (ffffffff81f28e7b)
Location: include/linux/skbuff.h:4206
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9e90)
Location: include/linux/skbuff.h:4206
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv6/ip6_output.c (ffffffff82086b52)
Location: include/linux/skbuff.h:4206
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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

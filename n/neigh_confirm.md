# Function: <code>neigh_confirm</code>

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
In net/core/filter.c (ffffffff81c43f79)
Location: include/net/neighbour.h:327
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81cce531)
Location: include/net/neighbour.h:327
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff81cd9817)
Location: include/net/neighbour.h:327
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81d878ec)
Location: include/net/neighbour.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81da159c)
Location: include/net/neighbour.h:327
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
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
In net/core/filter.c (ffffffff81df82c9)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81e8e751)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff81e99f97)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81f5566c)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81f708dc)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
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
In net/core/filter.c (ffffffff81e69930)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81eece5a)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff81ef8907)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81fb50db)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81fd0546)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
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
In net/core/filter.c (ffffffff81f28f9d)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81fb0eea)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
```
```
In net/ipv4/ip_output.c (ffffffff81fbc83a)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff8208266d)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8209ddd6)
Location: include/net/neighbour.h:324
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
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

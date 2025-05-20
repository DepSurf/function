# Function: <code>skb_unset_mac_header</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a31028)
Location: include/linux/skbuff.h:2557
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv6/seg6_local.c (ffffffff81b8eb9f)
Location: include/linux/skbuff.h:2557
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
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
In net/core/filter.c (ffffffff81a18068)
Location: include/linux/skbuff.h:2573
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv6/seg6_local.c (ffffffff81b7dc8f)
Location: include/linux/skbuff.h:2573
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
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
In net/core/filter.c (ffffffff81acb778)
Location: include/linux/skbuff.h:2602
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv6/seg6_local.c (ffffffff81c48fe1)
Location: include/linux/skbuff.h:2602
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
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
In net/core/filter.c (ffffffff81c47398)
Location: include/linux/skbuff.h:2971
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv6/seg6_local.c (ffffffff81de86e0)
Location: include/linux/skbuff.h:2971
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
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
In net/core/filter.c (ffffffff81dfb8f8)
Location: include/linux/skbuff.h:2865
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb820)
Location: include/linux/skbuff.h:2865
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
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
In net/core/filter.c (ffffffff81e6c7f8)
Location: include/linux/skbuff.h:2919
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv6/seg6_local.c (ffffffff8201bee2)
Location: include/linux/skbuff.h:2919
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
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
In net/core/filter.c (ffffffff81f2c0d8)
Location: include/linux/skbuff.h:2926
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv6/seg6_local.c (ffffffff820eaeae)
Location: include/linux/skbuff.h:2926
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
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

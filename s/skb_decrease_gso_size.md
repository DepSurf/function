# Function: <code>skb_decrease_gso_size</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b64f6)
Location: include/linux/skbuff.h:4067
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818db752)
Location: include/linux/skbuff.h:4236
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/filter.c (ffffffff819283f2)
Location: include/linux/skbuff.h:4343
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff81943882)
Location: include/linux/skbuff.h:4343
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (ffffffff8195a9dd)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff819777a3)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:handle_gso_type
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
In net/core/filter.c (ffffffff81a2c419)
Location: include/linux/skbuff.h:4467
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/lwt_bpf.c (ffffffff81a4c7bb)
Location: include/linux/skbuff.h:4467
Inline: True
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
In net/core/filter.c (ffffffff81a2d999)
Location: include/linux/skbuff.h:4496
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_proto_4_to_6
```
```
In net/core/lwt_bpf.c (ffffffff81a5243b)
Location: include/linux/skbuff.h:4496
Inline: True
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
In net/core/filter.c (ffffffff81a15258)
Location: include/linux/skbuff.h:4560
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81a37c1b)
Location: include/linux/skbuff.h:4560
Inline: True
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
In net/core/filter.c (ffffffff81ac679d)
Location: include/linux/skbuff.h:4599
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81aeebc7)
Location: include/linux/skbuff.h:4599
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (ffffffff81c42058)
Location: include/linux/skbuff.h:5021
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81c71aad)
Location: include/linux/skbuff.h:5021
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (ffffffff81df9523)
Location: include/linux/skbuff.h:4917
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81e29b9d)
Location: include/linux/skbuff.h:4917
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (ffffffff81e6adf1)
Location: include/linux/skbuff.h:4880
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81e9f340)
Location: include/linux/skbuff.h:4880
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (ffffffff81f29d81)
Location: include/linux/skbuff.h:4920
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81f61aad)
Location: include/linux/skbuff.h:4920
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (ffff800010bfc0f8)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffff800010c1f630)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (c0d171d8)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (c0d372c4)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
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
In net/core/filter.c (c000000000ce7660)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (c000000000d0fac8)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:handle_gso_type
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
In net/core/filter.c (ffffffe00077e990)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffe000797ca0)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:handle_gso_type
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
In net/core/filter.c (ffffffff818fa9ad)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff81917613)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:handle_gso_type
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
In net/core/filter.c (ffffffff818b47dd)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff818d13c3)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:handle_gso_type
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
In net/core/filter.c (ffffffff8194b9dd)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff819687a3)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:handle_gso_type
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
In net/core/filter.c (ffffffff8196d2ed)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
```
In net/core/lwt_bpf.c (ffffffff8198ab53)
Location: include/linux/skbuff.h:4427
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:handle_gso_type
```
</details>
</li>
</ul>

## Differences

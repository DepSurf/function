# Function: <code>skb_is_gso_sctp</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a47f)
Location: include/linux/skbuff.h:4047
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/filter.c (ffffffff818b6481)
Location: include/linux/skbuff.h:4047
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/skbuff.c (ffffffff8189b08f)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e576f)
Location: include/linux/skbuff.h:4317
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819178bf)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9eff)
Location: include/linux/skbuff.h:4441
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9c9f)
Location: include/linux/skbuff.h:4470
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
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
In net/core/skbuff.c (ffffffff819cfde1)
Location: include/linux/skbuff.h:4534
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7f811)
Location: include/linux/skbuff.h:4573
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3c6f)
Location: include/linux/skbuff.h:4995
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da19cf)
Location: include/linux/skbuff.h:4891
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81e7d48f)
Location: include/linux/skbuff.h:4854
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81f3e40f)
Location: include/linux/skbuff.h:4894
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0c6c)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccdfe8)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c86e80)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741e16)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b78bf)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187180f)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819088bf)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192996f)
Location: include/linux/skbuff.h:4401
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
</details>
</li>
</ul>

## Differences

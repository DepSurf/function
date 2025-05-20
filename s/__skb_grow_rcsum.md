# Function: <code>__skb_grow_rcsum</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cb5cd)
Location: include/linux/skbuff.h:2987
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eade3)
Location: include/linux/skbuff.h:3052
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818678be)
Location: include/linux/skbuff.h:3151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b56e4)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In net/core/filter.c (ffffffff818dc54f)
Location: include/linux/skbuff.h:3239
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffff8192965f)
Location: include/linux/skbuff.h:3326
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffff81955d31)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In net/core/filter.c (ffffffff81a2d5a1)
Location: include/linux/skbuff.h:3415
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In net/core/filter.c (ffffffff81a2ef61)
Location: include/linux/skbuff.h:3441
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In net/core/filter.c (ffffffff81a191e7)
Location: include/linux/skbuff.h:3505
Inline: True
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
In net/core/filter.c (ffffffff81ac7497)
Location: include/linux/skbuff.h:3542
Inline: True
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
In net/core/filter.c (ffffffff81c43d1e)
Location: include/linux/skbuff.h:3916
Inline: True
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
In net/core/filter.c (ffffffff81df7f0e)
Location: include/linux/skbuff.h:3812
Inline: True
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
In net/core/filter.c (ffffffff81e675f0)
Location: include/linux/skbuff.h:3846
Inline: True
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
In net/core/filter.c (ffffffff81f267b0)
Location: include/linux/skbuff.h:3874
Inline: True
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
In net/core/filter.c (ffff800010bfd11c)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (c0d17718)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (c000000000ce55e0)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffe00077fb22)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In net/core/filter.c (ffffffff818f5d01)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In net/core/filter.c (ffffffff818afb31)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In net/core/filter.c (ffffffff81946d31)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In net/core/filter.c (ffffffff81968641)
Location: include/linux/skbuff.h:3391
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
</details>
</li>
</ul>

## Differences

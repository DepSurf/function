# Function: <code>__skb_reset_checksum_unnecessary</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30939)
Location: include/linux/skbuff.h:3923
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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
In net/core/filter.c (ffffffff81a32c5f)
Location: include/linux/skbuff.h:3952
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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
In net/core/filter.c (ffffffff81a1a640)
Location: include/linux/skbuff.h:4016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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
In net/core/filter.c (ffffffff81acc920)
Location: include/linux/skbuff.h:4053
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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
In net/core/filter.c (ffffffff81c497f1)
Location: include/linux/skbuff.h:4472
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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
In net/core/filter.c (ffffffff81dfe7f4)
Location: include/linux/skbuff.h:4368
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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
In net/core/filter.c (ffffffff81e7080b)
Location: include/linux/skbuff.h:4400
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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
In net/core/filter.c (ffffffff81f2fe9b)
Location: include/linux/skbuff.h:4440
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_csum_level
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

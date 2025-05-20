# Function: <code>tls_sw_has_ctx_rx</code>

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
In net/core/skmsg.c (ffffffff81a3bbcc)
Location: include/net/tls.h:586
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81a2d454)
Location: include/net/tls.h:607
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81a3e55c)
Location: include/net/tls.h:607
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81a15466)
Location: include/net/tls.h:615
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81a4c75c)
Location: include/net/tls.h:615
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81ac6486)
Location: include/net/tls.h:608
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81b0507c)
Location: include/net/tls.h:608
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81c423f5)
Location: include/net/tls.h:607
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81c8a92c)
Location: include/net/tls.h:607
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81df8585)
Location: include/net/tls.h:418
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81e4554c)
Location: include/net/tls.h:418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81e6a4f5)
Location: include/net/tls.h:423
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81ea1a72)
Location: include/net/tls.h:423
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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
In net/core/filter.c (ffffffff81f29485)
Location: include/net/tls.h:399
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81f64282)
Location: include/net/tls.h:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
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

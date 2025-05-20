# Function: <code>skb_frag_page_copy</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191f526)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff819f266c)
Location: include/linux/skbuff.h:3047
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff819f266c)
Location: include/linux/skbuff.h:3073
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff819d8899)
Location: include/linux/skbuff.h:3137
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff81a887c8)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff81bfdfbe)
Location: include/linux/skbuff.h:3543
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff81daed00)
Location: include/linux/skbuff.h:3439
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff81e1ecc7)
Location: include/linux/skbuff.h:3499
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/tcp_output.c (ffffffff81f228b4)
Location: include/linux/skbuff.h:3499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
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
In net/core/skbuff.c (ffffffff81edc327)
Location: include/linux/skbuff.h:3524
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/tcp_output.c (ffffffff81fe62a4)
Location: include/linux/skbuff.h:3524
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
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
In net/core/skbuff.c (ffff800010bb9fd4)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (c0cd6890)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (c000000000c927e4)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffe0007493b4)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff818bf526)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff81879466)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff81910526)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
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
In net/core/skbuff.c (ffffffff81931686)
Location: include/linux/skbuff.h:3024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
```
</details>
</li>
</ul>

## Differences

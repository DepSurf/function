# Function: <code>skb_frag_off_copy</code>

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
In net/core/skbuff.c (ffffffff8191f52d)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (ffffffff819f267e)
Location: include/linux/skbuff.h:2951
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
In net/core/skbuff.c (ffffffff819f267e)
Location: include/linux/skbuff.h:2977
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
In net/core/skbuff.c (ffffffff819d88ab)
Location: include/linux/skbuff.h:3041
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
In net/core/skbuff.c (ffffffff81a887db)
Location: include/linux/skbuff.h:3070
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
In net/core/skbuff.c (ffffffff81bfdfd1)
Location: include/linux/skbuff.h:3439
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
In net/core/skbuff.c (ffffffff81daed13)
Location: include/linux/skbuff.h:3332
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
In net/core/skbuff.c (ffffffff81e1ecd7)
Location: include/linux/skbuff.h:3386
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/tcp_output.c (ffffffff81f228c6)
Location: include/linux/skbuff.h:3386
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
In net/core/skbuff.c (ffffffff81edc337)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/tcp_output.c (ffffffff81fe62b6)
Location: include/linux/skbuff.h:3409
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
In net/core/skbuff.c (ffff800010bb9fdc)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (c0cd68ac)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (c000000000c927f8)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (ffffffe0007493c0)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (ffffffff818bf52d)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (ffffffff8187946d)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (ffffffff8191052d)
Location: include/linux/skbuff.h:2928
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
In net/core/skbuff.c (ffffffff8193168d)
Location: include/linux/skbuff.h:2928
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
```
</details>
</li>
</ul>

## Differences

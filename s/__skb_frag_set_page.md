# Function: <code>__skb_frag_set_page</code>

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
In net/core/skbuff.c (ffffffff8191946f)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff819f2b23)
Location: include/linux/skbuff.h:3060
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff819f2b15)
Location: include/linux/skbuff.h:3086
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff819d8d4b)
Location: include/linux/skbuff.h:3150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff81a88ce3)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3556
Inline: True
```
```
In net/core/gro.c (ffffffff81c54cf0)
Location: include/linux/skbuff.h:3556
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81cb5a9e)
Location: include/linux/skbuff.h:3556
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3452
Inline: True
```
```
In net/core/gro.c (ffffffff81e0a47c)
Location: include/linux/skbuff.h:3452
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81e73f6e)
Location: include/linux/skbuff.h:3452
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/skbuff.c (ffff800010bb2524)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (c0ccfd44)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (c000000000c882f8)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffe000743d82)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff818b946f)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff818733bf)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff8190a46f)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
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
In net/core/skbuff.c (ffffffff8192b56f)
Location: include/linux/skbuff.h:3037
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
</details>
</li>
</ul>

## Differences

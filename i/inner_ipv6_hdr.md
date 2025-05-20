# Function: <code>inner_ipv6_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff817fd24a)
Location: include/linux/ipv6.h:82
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff8186cb7a)
Location: include/linux/ipv6.h:86
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff8189f96a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff818c5eae)
Location: include/linux/ipv6.h:95
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff8194923e)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff819a2326)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff819d8f96)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81a47803)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81a7e3b3)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81b79033)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81b87fb3)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81b76ce3)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/xfrm/xfrm_output.c (ffffffff81be149e)
Location: include/linux/ipv6.h:101
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41793)
Location: include/linux/ipv6.h:101
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/xfrm/xfrm_output.c (ffffffff81d783c2)
Location: include/linux/ipv6.h:103
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddff83)
Location: include/linux/ipv6.h:103
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/xfrm/xfrm_output.c (ffffffff81f44d9b)
Location: include/linux/ipv6.h:103
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb22b3)
Location: include/linux/ipv6.h:103
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/xfrm/xfrm_output.c (ffffffff81fa4485)
Location: include/linux/ipv6.h:103
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff820129c3)
Location: include/linux/ipv6.h:103
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/xfrm/xfrm_output.c (ffffffff820717f8)
Location: include/linux/ipv6.h:105
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1b23)
Location: include/linux/ipv6.h:105
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffff800010d49808)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (c0e4ab68)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (c000000000e7ee84)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffe000882c20)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81a1da43)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff819da803)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81a884c3)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
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
In net/ipv6/xfrm6_output.c (ffffffff81a95113)
Location: include/linux/ipv6.h:97
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
```
</details>
</li>
</ul>

## Differences

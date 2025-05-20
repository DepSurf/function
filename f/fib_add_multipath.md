# Function: <code>fib_add_multipath</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c9efa)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff81a00aba)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_add_multipath(struct sk_buff *skb, struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aed270)
Location: net/ipv4/fib_semantics.c:1696
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff81aed270-ffffffff81aed3f4: fib_add_multipath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_add_multipath(struct sk_buff *skb, struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afa3e0)
Location: net/ipv4/fib_semantics.c:1695
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff81afa3e0-ffffffff81afa564: fib_add_multipath (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (ffffffff81ae82ca)
Location: net/ipv4/fib_semantics.c:1696
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff81ba8331)
Location: net/ipv4/fib_semantics.c:1741
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff81d3ac9d)
Location: net/ipv4/fib_semantics.c:1728
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff81f0360d)
Location: net/ipv4/fib_semantics.c:1734
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff81f62fed)
Location: net/ipv4/fib_semantics.c:1734
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff820295bd)
Location: net/ipv4/fib_semantics.c:1741
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffff800010cb9088)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (c0dc4824)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (c000000000dd1ce8)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffe00080fe5c)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff819a085a)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff8195a31a)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff81a0b0fa)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
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
In net/ipv4/fib_semantics.c (ffffffff81a158da)
Location: net/ipv4/fib_semantics.c:1687
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>

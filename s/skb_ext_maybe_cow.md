# Function: <code>skb_ext_maybe_cow</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d1ed)
Location: net/core/skbuff.c:5614
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff818e7a6d)
Location: net/core/skbuff.c:5974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff81919f3d)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff819f42f1)
Location: net/core/skbuff.c:6110
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff819f4311)
Location: net/core/skbuff.c:6247
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff819da4d1)
Location: net/core/skbuff.c:6335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff81a8a4e1)
Location: net/core/skbuff.c:6410
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff81bff941)
Location: net/core/skbuff.c:6323
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct skb_ext *skb_ext_maybe_cow(struct skb_ext *old, unsigned int old_active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da4e80)
Location: net/core/skbuff.c:6524
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
```
**Symbols:**

```
ffffffff81da4e80-ffffffff81da4fc4: skb_ext_maybe_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct skb_ext *skb_ext_maybe_cow(struct skb_ext *old, unsigned int old_active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e13a40)
Location: net/core/skbuff.c:6569
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
```
**Symbols:**

```
ffffffff81e13a40-ffffffff81e13b84: skb_ext_maybe_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct skb_ext *skb_ext_maybe_cow(struct skb_ext *old, unsigned int old_active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed0c00)
Location: net/core/skbuff.c:6716
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
```
**Symbols:**

```
ffffffff81ed0c00-ffffffff81ed0d44: skb_ext_maybe_cow (STB_LOCAL)
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
In net/core/skbuff.c (ffff800010bb2678)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (c0cd08e4)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (c000000000c8a200)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffe0007445c2)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff818b9f3d)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff81873e8d)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff8190af3d)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
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
In net/core/skbuff.c (ffffffff8192c03d)
Location: net/core/skbuff.c:5991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

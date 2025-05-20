# Function: <code>___neigh_create</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:575
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff818c7c10-ffffffff818c8278: ___neigh_create (STB_LOCAL)
ffffffff818c8d14-ffffffff818c8d2a: ___neigh_create.cold.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:575
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81914670-ffffffff81914d55: ___neigh_create (STB_LOCAL)
ffffffff81915950-ffffffff81915966: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81946ce0-ffffffff819473c5: ___neigh_create (STB_LOCAL)
ffffffff81947f14-ffffffff81947f2a: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a17170)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81a17170-ffffffff81a1751f: ___neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a17460)
Location: net/core/neighbour.c:574
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81a17460-ffffffff81a177f0: ___neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819fe270)
Location: net/core/neighbour.c:578
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff819fe270-ffffffff819fe6fd: ___neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, u8 flags, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:580
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81ab0390-ffffffff81ab0857: ___neigh_create (STB_LOCAL)
ffffffff81d36c67-ffffffff81d36ce9: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, u32 flags, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:624
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81c29320-ffffffff81c298da: ___neigh_create (STB_LOCAL)
ffffffff81f03568-ffffffff81f03607: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, u32 flags, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:662
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81ddc090-ffffffff81ddc5e3: ___neigh_create (STB_LOCAL)
ffffffff820abd45-ffffffff820abdd5: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, u32 flags, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:631
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81e4cde0-ffffffff81e4d344: ___neigh_create (STB_LOCAL)
ffffffff8212d49b-ffffffff8212d52c: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, u32 flags, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:639
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81f0bb40-ffffffff81f0c0a1: ___neigh_create (STB_LOCAL)
ffffffff8220f1e8-ffffffff8220f279: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be7eb8)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffff800010be7eb8-ffff800010be877c: ___neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0d011d8)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
c0d011d8-c0d0197c: ___neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cca420)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
c000000000cca420-c000000000ccad70: ___neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076c5f2)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffe00076c5f2-ffffffe00076cc40: ___neigh_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff818e6cb0-ffffffff818e7395: ___neigh_create (STB_LOCAL)
ffffffff818e7ee4-ffffffff818e7efa: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff818a0af0-ffffffff818a11d5: ___neigh_create (STB_LOCAL)
ffffffff818a1d24-ffffffff818a1d3a: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff81937ce0-ffffffff819383c5: ___neigh_create (STB_LOCAL)
ffffffff81938f14-ffffffff81938f2a: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct neighbour *___neigh_create(struct neigh_table *tbl, const void *pkey, struct net_device *dev, bool exempt_from_gc, bool want_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:572
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
**Symbols:**

```
ffffffff819594c0-ffffffff81959bd4: ___neigh_create (STB_LOCAL)
ffffffff8195a724-ffffffff8195a73a: ___neigh_create.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>tbl, pkey, dev, exempt_from_gc, want_ref</code> ➡️ <code>tbl, pkey, dev, flags, exempt_from_gc, want_ref</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 flags</code> ➡️ <code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

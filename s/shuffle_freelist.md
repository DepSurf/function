# Function: <code>shuffle_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812082ca)
Location: mm/slub.c:1477
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff8121a324)
Location: mm/slub.c:1480
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff81225df5)
Location: mm/slub.c:1482
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff8124308b)
Location: mm/slub.c:1513
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff812648e1)
Location: mm/slub.c:1516
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff81279023)
Location: mm/slub.c:1574
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff8129425c)
Location: mm/slub.c:1591
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff812a3f4a)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff812d9a6a)
Location: mm/slub.c:1621
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff812e4dd4)
Location: mm/slub.c:1689
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff812ec9bb)
Location: mm/slub.c:1717
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff81334b88)
Location: mm/slub.c:1841
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff813a63ca)
Location: mm/slub.c:1903
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool shuffle_freelist(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81426da0)
Location: mm/slub.c:1932
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff81426da0-ffffffff81426f89: shuffle_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool shuffle_freelist(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145cb50)
Location: mm/slub.c:1943
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff8145cb50-ffffffff8145cd40: shuffle_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool shuffle_freelist(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81457260)
Location: mm/slub.c:2268
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff81457260-ffffffff81457450: shuffle_freelist (STB_LOCAL)
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
In mm/slub.c (ffff800010345cf4)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (c0549a74)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (c0000000004223d0)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffe00023846a)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff8129c52a)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff8128e0d7)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff8129a33a)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff812aa21a)
Location: mm/slub.c:1571
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
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

# Function: <code>slab_order</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int slab_order(int size, int min_objects, int max_order, int fract_leftover, int reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8890)
Location: mm/slub.c:3020
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
Direct callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
```
**Symbols:**

```
ffffffff811e8890-ffffffff811e8962: slab_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int slab_order(int size, int min_objects, int max_order, int fract_leftover, int reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120ca3e)
Location: mm/slub.c:3181
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
Direct callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
```
**Symbols:**

```
ffffffff81207630-ffffffff81207704: slab_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int slab_order(int size, int min_objects, int max_order, int fract_leftover, int reserved);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121ea9e)
Location: mm/slub.c:3203
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
Direct callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
```
**Symbols:**

```
ffffffff81219540-ffffffff81219614: slab_order (STB_LOCAL)
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
In mm/slub.c (ffffffff8122a630)
Location: mm/slub.c:3200
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff81245d64)
Location: mm/slub.c:3213
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int slab_order(unsigned int size, unsigned int min_objects, unsigned int max_order, unsigned int fract_leftover);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126449f)
Location: mm/slub.c:3194
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
Direct callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
```
**Symbols:**

```
ffffffff81263a50-ffffffff81263afb: slab_order (STB_LOCAL)
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
In mm/slub.c (ffffffff81279811)
Location: mm/slub.c:3244
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff812951d7)
Location: mm/slub.c:3255
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff812a4fb7)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff812d8a30)
Location: mm/slub.c:3323
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff812e5584)
Location: mm/slub.c:3396
Inline: True
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
In mm/slub.c (ffffffff812ebc3b)
Location: mm/slub.c:3430
Inline: True
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
In mm/slub.c (ffffffff81334618)
Location: mm/slub.c:3767
Inline: True
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
In mm/slub.c (ffffffff813a6514)
Location: mm/slab.h:183
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
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
In mm/slub.c (ffffffff8142795f)
Location: mm/slab.h:193
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
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
In mm/slub.c (ffffffff8145cec9)
Location: mm/slab.h:221
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
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
In mm/slub.c (ffffffff814575e6)
Location: mm/slab.h:212
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
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
In mm/slub.c (ffff800010344504)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (c054a8f8)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (c000000000423978)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffe000237d16)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff8129d597)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff8128f127)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff8129b3a7)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
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
In mm/slub.c (ffffffff812ab287)
Location: mm/slub.c:3265
Inline: True
Inline callers:
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
  - mm/slub.c:calculate_sizes
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>

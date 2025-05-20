# Function: <code>obj_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205e90)
Location: mm/zsmalloc.c:1438
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff81205e90-ffffffff81205fb3: obj_free.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122ac60)
Location: mm/zsmalloc.c:1595
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8122ac60-ffffffff8122ad24: obj_free.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123d1c0)
Location: mm/zsmalloc.c:1555
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8123d1c0-ffffffff8123d28b: obj_free.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812491b0)
Location: mm/zsmalloc.c:1534
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812491b0-ffffffff81249243: obj_free.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812693e0)
Location: mm/zsmalloc.c:1538
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812693e0-ffffffff81269474: obj_free.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128d2d0)
Location: mm/zsmalloc.c:1541
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8128d2d0-ffffffff8128d364: obj_free.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a2150)
Location: mm/zsmalloc.c:1528
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812a2150-ffffffff812a21e4: obj_free.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812bd2b0)
Location: mm/zsmalloc.c:1518
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812bd2b0-ffffffff812bd33f: obj_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812cf1a0)
Location: mm/zsmalloc.c:1515
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812cf1a0-ffffffff812cf22f: obj_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void obj_free(struct size_class *class, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81306130)
Location: mm/zsmalloc.c:1517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81306130-ffffffff813061c4: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void obj_free(struct size_class *class, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311e90)
Location: mm/zsmalloc.c:1466
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81311e90-ffffffff81311f24: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void obj_free(struct size_class *class, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81317d50)
Location: mm/zsmalloc.c:1465
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81317d50-ffffffff81317de7: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void obj_free(struct size_class *class, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81363fe0)
Location: mm/zsmalloc.c:1465
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81363fe0-ffffffff81364077: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void obj_free(int class_size, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e0db0)
Location: mm/zsmalloc.c:1465
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff813e0db0-ffffffff813e0e88: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void obj_free(int class_size, long unsigned int obj, long unsigned int *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81467f40)
Location: mm/zsmalloc.c:1619
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81467f40-ffffffff81468045: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void obj_free(int class_size, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149d220)
Location: mm/zsmalloc.c:1418
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8149d220-ffffffff8149d2f5: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void obj_free(int class_size, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cc9e0)
Location: mm/zsmalloc.c:1421
Inline: False
Direct callers:
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff814cc9e0-ffffffff814ccab5: obj_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffff800010373ef0)
Location: mm/zsmalloc.c:1515
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffff800010373ef0-ffff800010373fb0: obj_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void obj_free(struct size_class *class, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c05608b0)
Location: mm/zsmalloc.c:1515
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
c05608b0-c0560948: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void obj_free(struct size_class *class, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0000000004658e0)
Location: mm/zsmalloc.c:1515
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
c0000000004658e0-c0000000004659c0: obj_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void obj_free(struct size_class *class, long unsigned int obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024cc70)
Location: mm/zsmalloc.c:1515
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffe00024cc70-ffffffe00024cd18: obj_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c7780)
Location: mm/zsmalloc.c:1515
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812c7780-ffffffff812c780f: obj_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b87c0)
Location: mm/zsmalloc.c:1515
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812b87c0-ffffffff812b884f: obj_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c5590)
Location: mm/zsmalloc.c:1515
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812c5590-ffffffff812c561f: obj_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d6070)
Location: mm/zsmalloc.c:1515
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812d6070-ffffffff812d6117: obj_free.isra.0 (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int class_size</code>
</li>
<li>
<b>Param removed. </b>
<code>struct size_class *class</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *handle</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int *handle</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>

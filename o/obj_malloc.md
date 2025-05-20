# Function: <code>obj_malloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct page *first_page, struct size_class *class, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205930)
Location: mm/zsmalloc.c:1350
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff81205930-ffffffff81205a29: obj_malloc (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8122ad30)
Location: mm/zsmalloc.c:1487
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8122ad30-ffffffff8122ae3d: obj_malloc.isra.28 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8123d290)
Location: mm/zsmalloc.c:1447
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8123d290-ffffffff8123d3a5: obj_malloc.isra.30 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff81248c60)
Location: mm/zsmalloc.c:1426
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81248c60-ffffffff81248d3a: obj_malloc.isra.29 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff81268e90)
Location: mm/zsmalloc.c:1430
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81268e90-ffffffff81268f6a: obj_malloc.isra.30 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8128d1f0)
Location: mm/zsmalloc.c:1433
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8128d1f0-ffffffff8128d2cc: obj_malloc.isra.34 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff812a1f80)
Location: mm/zsmalloc.c:1420
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812a1f80-ffffffff812a205c: obj_malloc.isra.26 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff812bd740)
Location: mm/zsmalloc.c:1410
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812bd740-ffffffff812bd83b: obj_malloc.isra.0 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff812cf630)
Location: mm/zsmalloc.c:1407
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812cf630-ffffffff812cf72b: obj_malloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class *class, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81305bc0)
Location: mm/zsmalloc.c:1409
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81305bc0-ffffffff81305ca6: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class *class, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311920)
Location: mm/zsmalloc.c:1358
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81311920-ffffffff81311a06: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class *class, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81317910)
Location: mm/zsmalloc.c:1357
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81317910-ffffffff813179f7: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class *class, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81364080)
Location: mm/zsmalloc.c:1357
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81364080-ffffffff81364167: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct zs_pool *pool, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e0fe0)
Location: mm/zsmalloc.c:1353
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff813e0fe0-ffffffff813e1131: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct zs_pool *pool, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81468490)
Location: mm/zsmalloc.c:1507
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81468490-ffffffff814685e3: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct zs_pool *pool, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149d470)
Location: mm/zsmalloc.c:1307
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8149d470-ffffffff8149d5c4: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct zs_pool *pool, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814ccc30)
Location: mm/zsmalloc.c:1307
Inline: False
Direct callers:
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff814ccc30-ffffffff814ccd84: obj_malloc (STB_LOCAL)
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
In mm/zsmalloc.c (ffff800010373dc8)
Location: mm/zsmalloc.c:1407
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffff800010373dc8-ffff800010373ed8: obj_malloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class *class, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c056013c)
Location: mm/zsmalloc.c:1407
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
c056013c-c0560220: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class *class, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000465c10)
Location: mm/zsmalloc.c:1407
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
c000000000465c10-c000000000465d58: obj_malloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int obj_malloc(struct size_class *class, struct zspage *zspage, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024c8a8)
Location: mm/zsmalloc.c:1407
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffe00024c8a8-ffffffe00024c97a: obj_malloc (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff812c7c10)
Location: mm/zsmalloc.c:1407
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812c7c10-ffffffff812c7d0b: obj_malloc.isra.0 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff812b8c50)
Location: mm/zsmalloc.c:1407
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812b8c50-ffffffff812b8d4b: obj_malloc.isra.0 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff812c5a20)
Location: mm/zsmalloc.c:1407
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812c5a20-ffffffff812c5b1b: obj_malloc.isra.0 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff812d6760)
Location: mm/zsmalloc.c:1407
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812d6760-ffffffff812d6872: obj_malloc.isra.0 (STB_LOCAL)
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
<code>struct zs_pool *pool</code>
</li>
<li>
<b>Param removed. </b>
<code>struct size_class *class</code>
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
</ul>

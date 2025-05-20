# Function: <code>should_skip_region</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8127458b)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff8127458b-ffffffff812745d7: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8128339b)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff8128339b-ffffffff812833e7: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff812b53ec)
Location: mm/memblock.c:973
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff812b53ec-ffffffff812b543a: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_type *type, struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff812c04b0)
Location: mm/memblock.c:928
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff812c04b0-ffffffff812c050e: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_type *type, struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff812c5c50)
Location: mm/memblock.c:928
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff812c5c50-ffffffff812c5cb3: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool should_skip_region(struct memblock_type *type, struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff8130a58c)
Location: mm/memblock.c:963
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff8130a530-ffffffff8130a5b4: should_skip_region (STB_LOCAL)
ffffffff81cbe588-ffffffff81cbe5a3: should_skip_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool should_skip_region(struct memblock_type *type, struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:964
Inline: False
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff81372ff0-ffffffff813730a3: should_skip_region (STB_LOCAL)
ffffffff81e7056b-ffffffff81e70586: should_skip_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool should_skip_region(struct memblock_type *type, struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:982
Inline: False
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff813f0760-ffffffff813f0813: should_skip_region (STB_LOCAL)
ffffffff820656e7-ffffffff82065702: should_skip_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool should_skip_region(struct memblock_type *type, struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:995
Inline: False
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff814242f0-ffffffff814243a3: should_skip_region (STB_LOCAL)
ffffffff820e4ed8-ffffffff820e4ef3: should_skip_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool should_skip_region(struct memblock_type *type, struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:1053
Inline: False
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff81451110-ffffffff814511c3: should_skip_region (STB_LOCAL)
ffffffff821c1baf-ffffffff821c1bca: should_skip_region.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031b630)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffff80001031b630-ffff80001031b6c8: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c05355d8)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
c05355d8-c0535630: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003eef60)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
c0000000003eef60-c0000000003eeff0: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000220488)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffe000220488-ffffffe0002204e4: should_skip_region (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8127b9eb)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff8127b9eb-ffffffff8127ba37: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8126d8cb)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff8126d8cb-ffffffff8126d917: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8127978b)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff8127978b-ffffffff812797d7: should_skip_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool should_skip_region(struct memblock_region *m, int nid, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8128937b)
Location: mm/memblock.c:965
Inline: True
Direct callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
```
**Symbols:**

```
ffffffff8128937b-ffffffff812893c7: should_skip_region (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct memblock_type *type</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, nid, flags</code> ➡️ <code>type, m, nid, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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

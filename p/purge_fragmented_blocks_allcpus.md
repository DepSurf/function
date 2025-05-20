# Function: <code>purge_fragmented_blocks_allcpus</code>

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
In mm/vmalloc.c (ffffffff811cce3e)
Location: mm/vmalloc.c:926
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
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
In mm/vmalloc.c (ffffffff811e9eb2)
Location: mm/vmalloc.c:950
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fb440)
Location: mm/vmalloc.c:921
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff811fb440-ffffffff811fb622: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81206180)
Location: mm/vmalloc.c:972
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81206180-ffffffff8120635d: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121eea0)
Location: mm/vmalloc.c:970
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8121eea0-ffffffff8121f066: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81241770)
Location: mm/vmalloc.c:953
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81241770-ffffffff81241933: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255e70)
Location: mm/vmalloc.c:953
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81255e70-ffffffff81256033: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81268fd0)
Location: mm/vmalloc.c:1556
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81268fd0-ffffffff8126919c: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81277f00)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81277f00-ffffffff812780cc: purge_fragmented_blocks_allcpus (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff812a911d)
Location: mm/vmalloc.c:1665
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
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
In mm/vmalloc.c (ffffffff812b457d)
Location: mm/vmalloc.c:1654
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
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
In mm/vmalloc.c (ffffffff812b9c5d)
Location: mm/vmalloc.c:1924
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
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
In mm/vmalloc.c (ffffffff812fc25d)
Location: mm/vmalloc.c:1976
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81360f10)
Location: mm/vmalloc.c:1995
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
**Symbols:**

```
ffffffff81360f10-ffffffff81361116: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813dc900)
Location: mm/vmalloc.c:2057
Inline: False
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
**Symbols:**

```
ffffffff813dc900-ffffffff813dcb0a: purge_fragmented_blocks_allcpus (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff8141378b)
Location: mm/vmalloc.c:2153
Inline: True
Inline callers:
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
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
In mm/vmalloc.c (ffffffff814401fb)
Location: mm/vmalloc.c:2153
Inline: True
Inline callers:
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
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
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030e530)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffff80001030e530-ffff80001030e7ac: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0529f1c)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
c0529f1c-c052a150: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003df2d0)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
c0000000003df2d0-c0000000003df624: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000216f5c)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffe000216f5c-ffffffe000217188: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270550)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81270550-ffffffff8127071c: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812624c0)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812624c0-ffffffff8126268c: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e2f0)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8126e2f0-ffffffff8126e4bc: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void purge_fragmented_blocks_allcpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127dcb0)
Location: mm/vmalloc.c:1564
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8127dcb0-ffffffff8127de82: purge_fragmented_blocks_allcpus (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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

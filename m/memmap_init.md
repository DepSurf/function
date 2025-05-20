# Function: <code>memmap_init</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a251cf)
Location: mm/page_alloc.c:5802
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81a251cf-ffffffff81a251e0: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a95624)
Location: mm/page_alloc.c:5988
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81a95624-ffffffff81a95635: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accf07)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81accf07-ffffffff81accf18: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int range_start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc5830)
Location: mm/page_alloc.c:6089
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
```
**Symbols:**

```
ffffffff81bc5830-ffffffff81bc58fd: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int range_start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e762)
Location: mm/page_alloc.c:6303
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
```
**Symbols:**

```
ffffffff81c3e762-ffffffff81c3e8b8: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memmap_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f29d4)
Location: mm/page_alloc.c:6531
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff831f29d4-ffffffff831f2b73: memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memmap_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d8939)
Location: mm/page_alloc.c:6707
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff832d8939-ffffffff832d8adb: memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memmap_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348cec0)
Location: mm/page_alloc.c:6828
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff8348cec0-ffffffff8348d088: memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memmap_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebed40)
Location: mm/page_alloc.c:7000
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff83ebed40-ffffffff83ebef35: memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memmap_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e0830)
Location: mm/mm_init.c:923
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init
```
**Symbols:**

```
ffffffff836e0830-ffffffff836e0a25: memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memmap_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83913130)
Location: mm/mm_init.c:934
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init
```
**Symbols:**

```
ffffffff83913130-ffffffff83913325: memmap_init (STB_LOCAL)
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9fe80)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffff800010d9fe80-ffff800010d9fe9c: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c15bdd98)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
c15bdd98-c15bddc0: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eeca40)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
c000000000eeca40-c000000000eeca54: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000047228)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffe000047228-ffffffe000047244: memmap_init (STB_WEAK)
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6bd77)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81a6bd77-ffffffff81a6bd88: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a282be)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81a282be-ffffffff81a282cf: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad8187)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81ad8187-ffffffff81ad8198: memmap_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae4642)
Location: mm/page_alloc.c:6006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81ae4642-ffffffff81ae4653: memmap_init (STB_WEAK)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int range_start_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start_pfn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int zone</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int range_start_pfn</code>
</li>
</ul>
</details>
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

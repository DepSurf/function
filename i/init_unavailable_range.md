# Function: <code>init_unavailable_range</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 init_unavailable_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfb43e)
Location: mm/page_alloc.c:6920
Inline: False
Direct callers:
  - mm/page_alloc.c:init_unavailable_mem
  - mm/page_alloc.c:init_unavailable_mem
```
**Symbols:**

```
ffffffff82cfb43e-ffffffff82cfb4fe: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e3c3)
Location: mm/page_alloc.c:6275
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
```
**Symbols:**

```
ffffffff81c3e3c3-ffffffff81c3e448: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f27f5)
Location: mm/page_alloc.c:6477
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
```
**Symbols:**

```
ffffffff831f27f5-ffffffff831f28af: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d86d5)
Location: mm/page_alloc.c:6660
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
```
**Symbols:**

```
ffffffff832d86d5-ffffffff832d87b6: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348cc44)
Location: mm/page_alloc.c:6781
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
```
**Symbols:**

```
ffffffff8348cc44-ffffffff8348cd1c: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebe700)
Location: mm/page_alloc.c:6954
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
```
**Symbols:**

```
ffffffff83ebe700-ffffffff83ebe918: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e0470)
Location: mm/mm_init.c:807
Inline: False
Direct callers:
  - mm/mm_init.c:memmap_init
  - mm/mm_init.c:memmap_init
```
**Symbols:**

```
ffffffff836e0470-ffffffff836e0688: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83912cc0)
Location: mm/mm_init.c:818
Inline: False
Direct callers:
  - mm/mm_init.c:memmap_init
  - mm/mm_init.c:memmap_init
```
**Symbols:**

```
ffffffff83912cc0-ffffffff83912f23: init_unavailable_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int zone</code>
</li>
<li>
<b>Param added. </b>
<code>int node</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>void</code>
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

# Function: <code>calculate_min_free_kbytes</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void calculate_min_free_kbytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8649
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/khugepaged.c:set_recommended_min_free_kbytes
```
**Symbols:**

```
ffffffff81e70485-ffffffff81e70498: calculate_min_free_kbytes.cold (STB_LOCAL)
ffffffff81371950-ffffffff813719a5: calculate_min_free_kbytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void calculate_min_free_kbytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ef0b0)
Location: mm/page_alloc.c:8823
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/khugepaged.c:set_recommended_min_free_kbytes
```
**Symbols:**

```
ffffffff813ef0b0-ffffffff813ef11d: calculate_min_free_kbytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void calculate_min_free_kbytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81422f50)
Location: mm/page_alloc.c:5801
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/khugepaged.c:set_recommended_min_free_kbytes
```
**Symbols:**

```
ffffffff81422f50-ffffffff81422fbd: calculate_min_free_kbytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void calculate_min_free_kbytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144fe80)
Location: mm/page_alloc.c:5943
Inline: False
Direct callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/khugepaged.c:set_recommended_min_free_kbytes
```
**Symbols:**

```
ffffffff8144fe80-ffffffff8144feed: calculate_min_free_kbytes (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

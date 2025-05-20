# Function: <code>arch_has_descending_max_zone_pfns</code>

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
bool arch_has_descending_max_zone_pfns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b3b30)
Location: mm/page_alloc.c:7327
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff812b3b30-ffffffff812b3b3d: arch_has_descending_max_zone_pfns (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool arch_has_descending_max_zone_pfns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf600)
Location: mm/page_alloc.c:7474
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff812bf600-ffffffff812bf60d: arch_has_descending_max_zone_pfns (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool arch_has_descending_max_zone_pfns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c4c80)
Location: mm/page_alloc.c:7690
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff812c4c80-ffffffff812c4c8d: arch_has_descending_max_zone_pfns (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool arch_has_descending_max_zone_pfns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81309130)
Location: mm/page_alloc.c:7932
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff81309130-ffffffff8130913d: arch_has_descending_max_zone_pfns (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool arch_has_descending_max_zone_pfns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81371620)
Location: mm/page_alloc.c:8090
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff81371620-ffffffff81371631: arch_has_descending_max_zone_pfns (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool arch_has_descending_max_zone_pfns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813eed40)
Location: mm/page_alloc.c:8264
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff813eed40-ffffffff813eed51: arch_has_descending_max_zone_pfns (STB_WEAK)
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
In mm/mm_init.c (0)
Location: mm/mm_init.c:1773
Inline: True
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
In mm/mm_init.c (0)
Location: mm/mm_init.c:1771
Inline: True
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
</ul>

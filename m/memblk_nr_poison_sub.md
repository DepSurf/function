# Function: <code>memblk_nr_poison_sub</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memblk_nr_poison_sub(long unsigned int pfn, long int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b17090)
Location: drivers/base/memory.c:1191
Inline: False
Direct callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__free_raw_hwp_pages
```
**Symbols:**

```
ffffffff81b17090-ffffffff81b170ed: memblk_nr_poison_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memblk_nr_poison_sub(long unsigned int pfn, long int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b65e00)
Location: drivers/base/memory.c:1186
Inline: False
Direct callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
**Symbols:**

```
ffffffff81b65e00-ffffffff81b65e5d: memblk_nr_poison_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memblk_nr_poison_sub(long unsigned int pfn, long int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb9c80)
Location: drivers/base/memory.c:1239
Inline: False
Direct callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__folio_free_raw_hwp
```
**Symbols:**

```
ffffffff81bb9c80-ffffffff81bb9cdd: memblk_nr_poison_sub (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

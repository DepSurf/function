# Function: <code>__kernel_map_pages</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084a60)
Location: arch/x86/mm/pageattr.c:2271
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff81084a60-ffffffff81084aa8: __kernel_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085760)
Location: arch/x86/mm/pageattr.c:2161
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81085760-ffffffff810857a8: __kernel_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f540)
Location: arch/x86/mm/pat/set_memory.c:2197
Inline: False
Direct callers:
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:safe_copy_page
```
**Symbols:**

```
ffffffff8108f540-ffffffff8108f567: __kernel_map_pages (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b0618)
Location: arch/arm64/mm/pageattr.c:181
Inline: False
```
**Symbols:**

```
ffff8000100b0618-ffff8000100b067c: __kernel_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (c054828c)
Location: mm/page_poison.c:130
Inline: False
```
**Symbols:**

```
c054828c-c05482a4: __kernel_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffe00023678a)
Location: mm/page_poison.c:130
Inline: False
```
**Symbols:**

```
ffffffe00023678a-ffffffe0002367a4: __kernel_map_pages (STB_GLOBAL)
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
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084760)
Location: arch/x86/mm/pageattr.c:2161
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81084760-ffffffff810847a8: __kernel_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073370)
Location: arch/x86/mm/pageattr.c:2161
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81073370-ffffffff810733a7: __kernel_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084710)
Location: arch/x86/mm/pageattr.c:2161
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81084710-ffffffff81084758: __kernel_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __kernel_map_pages(struct page *page, int numpages, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086850)
Location: arch/x86/mm/pageattr.c:2161
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
**Symbols:**

```
ffffffff81086850-ffffffff810868a5: __kernel_map_pages (STB_GLOBAL)
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

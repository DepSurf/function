# Function: <code>__set_pages_p</code>

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
int __set_pages_p(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810838e0)
Location: arch/x86/mm/pageattr.c:2223
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_default_noflush
```
**Symbols:**

```
ffffffff810838e0-ffffffff8108395a: __set_pages_p (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __set_pages_p(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810849b0)
Location: arch/x86/mm/pageattr.c:2113
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_default_noflush
```
**Symbols:**

```
ffffffff810849b0-ffffffff81084a2a: __set_pages_p (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __set_pages_p(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f4ea)
Location: arch/x86/mm/pat/set_memory.c:2149
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__kernel_map_pages
```
**Symbols:**

```
ffffffff8108e5c0-ffffffff8108e63a: __set_pages_p (STB_LOCAL)
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108f2da)
Location: arch/x86/mm/pat/set_memory.c:2149
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108fe6a)
Location: arch/x86/mm/pat/set_memory.c:2157
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109f94a)
Location: arch/x86/mm/pat/set_memory.c:2157
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b376a)
Location: arch/x86/mm/pat/set_memory.c:2208
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce34d)
Location: arch/x86/mm/pat/set_memory.c:2312
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d190d)
Location: arch/x86/mm/pat/set_memory.c:2311
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff810da03d)
Location: arch/x86/mm/pat/set_memory.c:2315
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_default_noflush
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __set_pages_p(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810839b0)
Location: arch/x86/mm/pageattr.c:2113
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_default_noflush
```
**Symbols:**

```
ffffffff810839b0-ffffffff81083a2a: __set_pages_p (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __set_pages_p(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072600)
Location: arch/x86/mm/pageattr.c:2113
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_default_noflush
```
**Symbols:**

```
ffffffff81072600-ffffffff8107267a: __set_pages_p (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __set_pages_p(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083960)
Location: arch/x86/mm/pageattr.c:2113
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_default_noflush
```
**Symbols:**

```
ffffffff81083960-ffffffff810839da: __set_pages_p (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __set_pages_p(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085aa0)
Location: arch/x86/mm/pageattr.c:2113
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_default_noflush
```
**Symbols:**

```
ffffffff81085aa0-ffffffff81085b1a: __set_pages_p (STB_LOCAL)
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

# Function: <code>__set_pages_np</code>

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
int __set_pages_np(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083860)
Location: arch/x86/mm/pageattr.c:2242
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush
```
**Symbols:**

```
ffffffff81083860-ffffffff810838da: __set_pages_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __set_pages_np(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084930)
Location: arch/x86/mm/pageattr.c:2132
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush
```
**Symbols:**

```
ffffffff81084930-ffffffff810849aa: __set_pages_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __set_pages_np(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f46a)
Location: arch/x86/mm/pat/set_memory.c:2168
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__kernel_map_pages
```
**Symbols:**

```
ffffffff8108e540-ffffffff8108e5ba: __set_pages_np (STB_LOCAL)
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108f25a)
Location: arch/x86/mm/pat/set_memory.c:2168
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108fdea)
Location: arch/x86/mm/pat/set_memory.c:2176
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109f8ca)
Location: arch/x86/mm/pat/set_memory.c:2176
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b36da)
Location: arch/x86/mm/pat/set_memory.c:2227
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff810ce29d)
Location: arch/x86/mm/pat/set_memory.c:2331
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d185d)
Location: arch/x86/mm/pat/set_memory.c:2330
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d9f8d)
Location: arch/x86/mm/pat/set_memory.c:2334
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_direct_map_invalid_noflush
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
int __set_pages_np(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083930)
Location: arch/x86/mm/pageattr.c:2132
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush
```
**Symbols:**

```
ffffffff81083930-ffffffff810839aa: __set_pages_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __set_pages_np(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072580)
Location: arch/x86/mm/pageattr.c:2132
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush
```
**Symbols:**

```
ffffffff81072580-ffffffff810725fa: __set_pages_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __set_pages_np(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810838e0)
Location: arch/x86/mm/pageattr.c:2132
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush
```
**Symbols:**

```
ffffffff810838e0-ffffffff8108395a: __set_pages_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __set_pages_np(struct page *page, int numpages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085a20)
Location: arch/x86/mm/pageattr.c:2132
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:set_direct_map_invalid_noflush
```
**Symbols:**

```
ffffffff81085a20-ffffffff81085a9a: __set_pages_np (STB_LOCAL)
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

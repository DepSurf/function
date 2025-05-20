# Function: <code>do_set_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_set_pte(struct vm_area_struct *vma, long unsigned int address, struct page *page, pte_t *pte, bool write, bool anon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811be8c0)
Location: mm/memory.c:2810
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811be8c0-ffffffff811be9c0: do_set_pte (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_set_pte(struct vm_fault *vmf, struct page *page, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a1990)
Location: mm/memory.c:3822
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff812a1990-ffffffff812a1a7f: do_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_set_pte(struct vm_fault *vmf, struct page *page, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e2960)
Location: mm/memory.c:3967
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff812e2960-ffffffff812e2a4f: do_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_set_pte(struct vm_fault *vmf, struct page *page, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813431e0)
Location: mm/memory.c:4283
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff813431e0-ffffffff81343392: do_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_set_pte(struct vm_fault *vmf, struct page *page, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bb130)
Location: mm/memory.c:4284
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff813bb130-ffffffff813bb3c2: do_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_set_pte(struct vm_fault *vmf, struct page *page, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813efc80)
Location: mm/memory.c:4316
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/memory.c:finish_fault
```
**Symbols:**

```
ffffffff813efc80-ffffffff813efef3: do_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>

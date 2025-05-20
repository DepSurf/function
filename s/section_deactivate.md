# Function: <code>section_deactivate</code>

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
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8128da10)
Location: mm/sparse.c:725
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff8128da10-ffffffff8128dbad: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8129d660)
Location: mm/sparse.c:737
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff8129d660-ffffffff8129d85f: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d1370)
Location: mm/sparse.c:793
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:section_activate
```
**Symbols:**

```
ffffffff812d1370-ffffffff812d14dd: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dce90)
Location: mm/sparse.c:796
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:section_activate
```
**Symbols:**

```
ffffffff812dce90-ffffffff812dcffa: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812e4620)
Location: mm/sparse.c:804
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff812e4620-ffffffff812e484a: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8132b930)
Location: mm/sparse.c:777
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff8132b930-ffffffff8132bb5a: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8139b560)
Location: mm/sparse.c:780
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff8139b560-ffffffff8139b7e6: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8141b5a0)
Location: mm/sparse.c:780
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff8141b5a0-ffffffff8141b826: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8144eb40)
Location: mm/sparse.c:780
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff8144eb40-ffffffff8144edc6: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff814886e0)
Location: mm/sparse.c:779
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff814886e0-ffffffff81488981: section_deactivate (STB_LOCAL)
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
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff80001033c730)
Location: mm/sparse.c:737
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffff80001033c730-ffff80001033c9a0: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000417820)
Location: mm/sparse.c:737
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:section_activate
```
**Symbols:**

```
c000000000417820-c000000000417a74: section_deactivate (STB_LOCAL)
```
</details>
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
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81295c40)
Location: mm/sparse.c:737
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff81295c40-ffffffff81295e3f: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81287850)
Location: mm/sparse.c:737
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff81287850-ffffffff81287a4f: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81293a50)
Location: mm/sparse.c:737
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff81293a50-ffffffff81293c4f: section_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void section_deactivate(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812a38b0)
Location: mm/sparse.c:737
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff812a38b0-ffffffff812a3aaf: section_deactivate (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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

# Function: <code>__hugepage_set_anon_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __hugepage_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811ca4e0)
Location: mm/rmap.c:1679
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
```
**Symbols:**

```
ffffffff811ca4e0-ffffffff811ca53f: __hugepage_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __hugepage_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e69d0)
Location: mm/rmap.c:1878
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
```
**Symbols:**

```
ffffffff811e69d0-ffffffff811e6a3f: __hugepage_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __hugepage_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f7d70)
Location: mm/rmap.c:1877
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
```
**Symbols:**

```
ffffffff811f7d70-ffffffff811f7ddf: __hugepage_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __hugepage_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203300)
Location: mm/rmap.c:1785
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
```
**Symbols:**

```
ffffffff81203300-ffffffff81203370: __hugepage_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __hugepage_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121be40)
Location: mm/rmap.c:1870
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
```
**Symbols:**

```
ffffffff8121be40-ffffffff8121beae: __hugepage_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __hugepage_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123dc70)
Location: mm/rmap.c:1888
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
```
**Symbols:**

```
ffffffff8123dc70-ffffffff8123dce0: __hugepage_set_anon_rmap (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>

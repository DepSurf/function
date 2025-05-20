# Function: <code>vunmap_range_noflush</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bc2b0)
Location: mm/vmalloc.c:393
Inline: False
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_map_pages
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
```
**Symbols:**

```
ffffffff812bc2b0-ffffffff812bc5d4: vunmap_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:421
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
```
**Symbols:**

```
ffffffff81cbcf81-ffffffff81cbcfe1: vunmap_range_noflush.cold (STB_LOCAL)
ffffffff812fe8f0-ffffffff812fed4d: vunmap_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:419
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
```
**Symbols:**

```
ffffffff81e6ec32-ffffffff81e6ecbf: vunmap_range_noflush.cold (STB_LOCAL)
ffffffff813659e0-ffffffff81365b7e: vunmap_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e1ed0)
Location: mm/vmalloc.c:447
Inline: True
Inline callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
```
**Symbols:**

```
ffffffff813e19f0-ffffffff813e1a08: vunmap_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416bb5)
Location: mm/vmalloc.c:436
Inline: True
Inline callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
```
**Symbols:**

```
ffffffff81416780-ffffffff81416798: vunmap_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81443685)
Location: mm/vmalloc.c:436
Inline: True
Inline callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
Direct callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
```
**Symbols:**

```
ffffffff81443250-ffffffff81443268: vunmap_range_noflush (STB_GLOBAL)
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

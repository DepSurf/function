# Function: <code>__vunmap_range_noflush</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:425
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
```
**Symbols:**

```
ffffffff82064b2b-ffffffff82064ba4: __vunmap_range_noflush.cold (STB_LOCAL)
ffffffff813e1500-ffffffff813e168e: __vunmap_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:414
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
```
**Symbols:**

```
ffffffff820e426f-ffffffff820e42e8: __vunmap_range_noflush.cold (STB_LOCAL)
ffffffff81416270-ffffffff814163fe: __vunmap_range_noflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __vunmap_range_noflush(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:414
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:vunmap_range
```
**Symbols:**

```
ffffffff821c0ea3-ffffffff821c0f1c: __vunmap_range_noflush.cold (STB_LOCAL)
ffffffff81442d40-ffffffff81442ece: __vunmap_range_noflush (STB_GLOBAL)
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

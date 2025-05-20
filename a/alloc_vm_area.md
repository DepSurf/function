# Function: <code>alloc_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cefa0)
Location: mm/vmalloc.c:2243
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff811cefa0-ffffffff811cf041: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec130)
Location: mm/vmalloc.c:2264
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff811ec130-ffffffff811ec1d1: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd370)
Location: mm/vmalloc.c:2277
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff811fd370-ffffffff811fd411: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81208050)
Location: mm/vmalloc.c:2347
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81208050-ffffffff812080eb: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81221130)
Location: mm/vmalloc.c:2343
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81221130-ffffffff812211cb: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242fe0)
Location: mm/vmalloc.c:2330
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81242fe0-ffffffff8124307b: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812576f0)
Location: mm/vmalloc.c:2332
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff812576f0-ffffffff81257788: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a4a0)
Location: mm/vmalloc.c:3083
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8126a4a0-ffffffff8126a53c: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812793b0)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff812793b0-ffffffff8127944c: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac190)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812ac190-ffffffff812ac217: alloc_vm_area (STB_GLOBAL)
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
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030fe10)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
```
**Symbols:**

```
ffff80001030fe10-ffff80001030feb8: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c2e0)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
```
**Symbols:**

```
c052c2e0-c052c364: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e10b0)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
```
**Symbols:**

```
c0000000003e10b0-c0000000003e1180: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe00021833e)
Location: mm/vmalloc.c:3094
Inline: False
```
**Symbols:**

```
ffffffe00021833e-ffffffe0002183c4: alloc_vm_area (STB_GLOBAL)
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
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271a00)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81271a00-ffffffff81271a9c: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263970)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
```
**Symbols:**

```
ffffffff81263970-ffffffff81263a0c: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f7a0)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8126f7a0-ffffffff8126f83c: alloc_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_struct *alloc_vm_area(size_t size, pte_t **ptes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f1b0)
Location: mm/vmalloc.c:3094
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_cpu_prepare
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8127f1b0-ffffffff8127f24c: alloc_vm_area (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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

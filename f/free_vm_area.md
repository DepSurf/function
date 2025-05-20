# Function: <code>free_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cef70)
Location: mm/vmalloc.c:2266
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
  - drivers/acpi/apei/ghes.c:ghes_exit
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff811cef70-ffffffff811cef98: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec100)
Location: mm/vmalloc.c:2287
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff811ec100-ffffffff811ec128: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd340)
Location: mm/vmalloc.c:2300
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff811fd340-ffffffff811fd368: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81208020)
Location: mm/vmalloc.c:2370
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81208020-ffffffff81208048: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81221100)
Location: mm/vmalloc.c:2366
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81221100-ffffffff81221128: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242fb0)
Location: mm/vmalloc.c:2353
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81242fb0-ffffffff81242fd8: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812576c0)
Location: mm/vmalloc.c:2355
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff812576c0-ffffffff812576e8: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812693b0)
Location: mm/vmalloc.c:3106
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff812693b0-ffffffff812693da: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812782f0)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff812782f0-ffffffff8127831a: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812acb08)
Location: mm/vmalloc.c:3117
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:alloc_vm_area
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812ac160-ffffffff812ac18c: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b8038)
Location: mm/vmalloc.c:3102
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap_pfn
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812b76c0-ffffffff812b76ec: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bdbf8)
Location: mm/vmalloc.c:3354
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:vmap_pfn
  - mm/vmalloc.c:vmap_pfn
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812bcf90-ffffffff812bcfbc: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813003c8)
Location: mm/vmalloc.c:3465
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:vmap_pfn
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812ff700-ffffffff812ff72c: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81367728)
Location: mm/vmalloc.c:3627
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff81366880-ffffffff813668b3: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e3698)
Location: mm/vmalloc.c:3689
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff813e24f0-ffffffff813e2523: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814183c8)
Location: mm/vmalloc.c:3922
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff81416d80-ffffffff81416db3: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81444f18)
Location: mm/vmalloc.c:3922
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap_pfn
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff81443850-ffffffff81443883: free_vm_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030ea98)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
```
**Symbols:**

```
ffff80001030ea98-ffff80001030ead4: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a3f8)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
```
**Symbols:**

```
c052a3f8-c052a42c: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dfa70)
Location: mm/vmalloc.c:3117
Inline: False
Direct callers:
  - arch/powerpc/mm/ioremap.c:do_ioremap
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
```
**Symbols:**

```
c0000000003dfa70-c0000000003dfacc: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000217456)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - arch/riscv/mm/ioremap.c:ioremap
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffe000217456-ffffffe00021748e: free_vm_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270940)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81270940-ffffffff8127096a: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812628b0)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
```
**Symbols:**

```
ffffffff812628b0-ffffffff812628da: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e6e0)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8126e6e0-ffffffff8126e70a: free_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_vm_area(struct vm_struct *area);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e0b0)
Location: mm/vmalloc.c:3117
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - mm/vmalloc.c:pcpu_free_vm_areas
  - mm/vmalloc.c:alloc_vm_area
  - mm/zsmalloc.c:zs_cpu_dead
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8127e0b0-ffffffff8127e0da: free_vm_area (STB_GLOBAL)
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

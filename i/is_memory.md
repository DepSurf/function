# Function: <code>is_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_memory(struct acpi_resource *res, void *not_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81487734)
Location: drivers/acpi/acpi_lpss.c:259
Inline: False
```
**Symbols:**

```
ffffffff81487734-ffffffff81487775: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int is_memory(struct acpi_resource *res, void *not_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814d6347)
Location: drivers/acpi/acpi_lpss.c:291
Inline: False
```
**Symbols:**

```
ffffffff814d6347-ffffffff814d6388: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int is_memory(struct acpi_resource *res, void *not_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814f89a7)
Location: drivers/acpi/acpi_lpss.c:302
Inline: False
```
**Symbols:**

```
ffffffff814f89a7-ffffffff814f89e8: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *res, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815078f0)
Location: drivers/acpi/acpi_lpss.c:346
Inline: False
```
```
In drivers/nvdimm/core.c (ffffffff8162c84b)
Location: drivers/nvdimm/nd-core.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/bus.c (ffffffff8162d8b4)
Location: drivers/nvdimm/nd-core.h:73
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f166)
Location: drivers/nvdimm/nd-core.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff816314eb)
Location: drivers/nvdimm/nd-core.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636f0b)
Location: drivers/nvdimm/nd-core.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163b695)
Location: drivers/nvdimm/nd-core.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff8163c7ed)
Location: drivers/nvdimm/nd-core.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815078f0-ffffffff81507931: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81542960)
Location: drivers/acpi/resource.c:639
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81549d70)
Location: drivers/acpi/acpi_lpss.c:346
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff81696074)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816978d6)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff81699dcb)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169ebf5)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff816a240b)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816a4405)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff816a547d)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81542960-ffffffff815429fc: is_memory (STB_LOCAL)
ffffffff81549d70-ffffffff81549db1: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815788b0)
Location: drivers/acpi/resource.c:639
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8157fed0)
Location: drivers/acpi/acpi_lpss.c:353
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff816d2144)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3a15)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d607b)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816daccb)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff816de585)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e05e5)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff816e1685)
Location: drivers/nvdimm/nd-core.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815788b0-ffffffff8157894c: is_memory (STB_LOCAL)
ffffffff8157fed0-ffffffff8157ff11: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81590520)
Location: drivers/acpi/resource.c:639
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81597c10)
Location: drivers/acpi/acpi_lpss.c:377
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff816f39a4)
Location: drivers/nvdimm/nd-core.h:128
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5155)
Location: drivers/nvdimm/nd-core.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f7d9b)
Location: drivers/nvdimm/nd-core.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fcc8a)
Location: drivers/nvdimm/nd-core.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff81700945)
Location: drivers/nvdimm/nd-core.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817029b4)
Location: drivers/nvdimm/nd-core.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81703cd5)
Location: drivers/nvdimm/nd-core.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81590520-ffffffff815905bc: is_memory (STB_LOCAL)
ffffffff81597c10-ffffffff81597c51: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815c12f0)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c8db0)
Location: drivers/acpi/acpi_lpss.c:374
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8172cd06)
Location: drivers/nvdimm/nd-core.h:122
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172ea05)
Location: drivers/nvdimm/nd-core.h:122
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff81731495)
Location: drivers/nvdimm/nd-core.h:122
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736ec6)
Location: drivers/nvdimm/nd-core.h:122
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff8173a7b5)
Location: drivers/nvdimm/nd-core.h:122
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173c853)
Location: drivers/nvdimm/nd-core.h:122
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff8173d915)
Location: drivers/nvdimm/nd-core.h:122
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815c12f0-ffffffff815c1388: is_memory (STB_LOCAL)
ffffffff815c8db0-ffffffff815c8df1: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815e25b0)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815e9fd0)
Location: drivers/acpi/acpi_lpss.c:377
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff817513f5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81752cc5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff817555c5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff81756b7f)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175ac65)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff8175e485)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81760544)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81761745)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815e25b0-ffffffff815e2648: is_memory (STB_LOCAL)
ffffffff815e9fd0-ffffffff815ea011: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d410)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816959e0)
Location: drivers/acpi/acpi_lpss.c:370
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8180f755)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818119f5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff818135e5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff8181616f)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a921)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
```
```
In drivers/nvdimm/badrange.c (ffffffff8181e045)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81820045)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff818213d5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8168d410-ffffffff8168d4a8: is_memory (STB_LOCAL)
ffffffff816959e0-ffffffff81695a21: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816ab110)
Location: drivers/acpi/resource.c:624
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b2b10)
Location: drivers/acpi/acpi_lpss.c:377
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8181e6a2)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818207f7)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff818227d5)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff818252ff)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81829a41)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
```
```
In drivers/nvdimm/badrange.c (ffffffff8182cfce)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182ef75)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff818300ee)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff816ab110-ffffffff816ab1a8: is_memory (STB_LOCAL)
ffffffff816b2b10-ffffffff816b2b51: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d970)
Location: drivers/acpi/resource.c:669
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81694da0)
Location: drivers/acpi/acpi_lpss.c:377
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff81801b92)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803ad4)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff81805e37)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff8180868f)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180cc51)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff81810260)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81812225)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff8181337e)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8168d970-ffffffff8168da08: is_memory (STB_LOCAL)
ffffffff81694da0-ffffffff81694de1: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff817031a0)
Location: drivers/acpi/resource.c:676
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170aa90)
Location: drivers/acpi/acpi_lpss.c:376
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8188bf02)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e8d4)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff818911d7)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff81892e4f)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818971bc)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff8189a880)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c835)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff8189d9ce)
Location: drivers/nvdimm/nd-core.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff817031a0-ffffffff81703238: is_memory (STB_LOCAL)
ffffffff8170aa90-ffffffff8170aad1: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81831150)
Location: drivers/acpi/resource.c:676
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81838fa0)
Location: drivers/acpi/acpi_lpss.c:395
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/region_devs.c (ffffffff819dae30)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff819dcd3f)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/badrange.c (ffffffff819e3fbb)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e60f4)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff819e73dd)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81831150-ffffffff818311f4: is_memory (STB_LOCAL)
ffffffff81838fa0-ffffffff81838ffe: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81964210)
Location: drivers/acpi/resource.c:793
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b56220)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff81b5841f)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/badrange.c (ffffffff81b5fcab)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b62094)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81b635ed)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81964210-ffffffff819642cf: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819aa6a0)
Location: drivers/acpi/resource.c:834
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba9770)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff81bab98f)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/badrange.c (ffffffff81bb324b)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5694)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81bb6bed)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff819aa6a0-ffffffff819aa75f: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819f4930)
Location: drivers/acpi/resource.c:897
Inline: False
```
```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfdab0)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:align_store
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:nstype_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff81bffccf)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd-core.h:92
Inline: False
```
```
In drivers/nvdimm/badrange.c (ffffffff81c0773b)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c09c14)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81c0b23d)
Location: drivers/nvdimm/nd-core.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff819f4930-ffffffff819f49ef: is_memory (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffff80001076f000)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/nvdimm/bus.c (ffff80001095139c)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffff80001095342c)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffff800010956778)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffff80001095808c)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095c3a8)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffff80001095fbac)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/firmware/efi/arm-init.c (ffff8000114a7344)
Location: drivers/firmware/efi/arm-init.c:26
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
```
**Symbols:**

```
ffff80001076f000-ffff80001076f0bc: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/arm-init.c (c15a9ba4)
Location: drivers/firmware/efi/arm-init.c:26
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fde50)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00b9c)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (c000000000a0449c)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (c000000000a064c0)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0d8a0)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (c000000000a12708)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a15a30)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (c000000000a17150)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c168a)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2de8)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c5ace)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffe0005c6cac)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca6de)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffe0005cd7a0)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d4870)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff81705ae5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817073b5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff81709cb5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff8170b26f)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f355)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff81712b75)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81714c34)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81715e35)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815d4870-ffffffff815d4908: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815be430)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c4a40)
Location: drivers/acpi/acpi_lpss.c:377
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff816d9565)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dae35)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dd735)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff816decef)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2dd5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff816e65f5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e86b4)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff816e98b5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815be430-ffffffff815be4c8: is_memory (STB_LOCAL)
ffffffff815c4a40-ffffffff815c4a81: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d6890)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815de2b0)
Location: drivers/acpi/acpi_lpss.c:377
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff817448b5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746185)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff81748a85)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff8174a03f)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174e125)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff81751945)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753a04)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81754c05)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815d6890-ffffffff815d6928: is_memory (STB_LOCAL)
ffffffff815de2b0-ffffffff815de2f1: is_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int is_memory(struct acpi_resource *ares, void *not_used);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815f0750)
Location: drivers/acpi/resource.c:631
Inline: False
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f8170)
Location: drivers/acpi/acpi_lpss.c:377
Inline: False
```
```
In drivers/nvdimm/bus.c (ffffffff8175fcf5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817615c5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
```
In drivers/nvdimm/region_devs.c (ffffffff81763f05)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:region_visible
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/region_devs.c:size_show
```
```
In drivers/nvdimm/region.c (ffffffff817654bf)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817695a5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/badrange.c (ffffffff8176cea5)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176ee74)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81770075)
Location: drivers/nvdimm/nd-core.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815f0750-ffffffff815f07e8: is_memory (STB_LOCAL)
ffffffff815f8170-ffffffff815f81b1: is_memory (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_resource *ares</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_resource *res</code>
</li>
</ul>
</details>
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

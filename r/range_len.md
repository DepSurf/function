# Function: <code>range_len</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81316016)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pageunmap_range
  - mm/memremap.c:pageunmap_range
  - mm/memremap.c:pageunmap_range
  - mm/memremap.c:pageunmap_range
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81834c75)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_validate_align
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/bus.c:dax_bus_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131c252)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81817e41)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/bus.c:dax_bus_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8136953e)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818a246b)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/bus.c:dax_bus_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813e768a)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/dax/bus.c (ffffffff819ebca5)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/bus.c:dax_bus_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8146f30a)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
```
```
In drivers/pci/p2pdma.c (ffffffff8191c37a)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81b688a2)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/bus.c:dax_bus_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814a3aed)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
```
```
In drivers/pci/p2pdma.c (ffffffff8195f96c)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81bbbcfb)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/bus.c:dax_bus_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814d498e)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
```
```
In drivers/pci/p2pdma.c (ffffffff819a8fdb)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/range.h:11
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81c10483)
Location: include/linux/range.h:11
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/bus.c:dax_bus_probe
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

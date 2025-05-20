# Function: <code>to_namespace_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff815995c8)
Location: drivers/nvdimm/nd.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
```
In drivers/nvdimm/label.c (ffffffff8159ea05)
Location: drivers/nvdimm/nd.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:preamble_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff815ef0ae)
Location: drivers/nvdimm/nd.h:77
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
```
In drivers/nvdimm/label.c (ffffffff815f67d4)
Location: drivers/nvdimm/nd.h:77
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:preamble_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff8161c23f)
Location: drivers/nvdimm/nd.h:77
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81624740)
Location: drivers/nvdimm/nd.h:77
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:preamble_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81630281)
Location: drivers/nvdimm/nd.h:78
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff8163127a)
Location: drivers/nvdimm/nd.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636e9f)
Location: drivers/nvdimm/nd.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff816396d8)
Location: drivers/nvdimm/nd.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff81698aaa)
Location: drivers/nvdimm/nd.h:72
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff81699aaa)
Location: drivers/nvdimm/nd.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e99d)
Location: drivers/nvdimm/nd.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff816a1db6)
Location: drivers/nvdimm/nd.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm.c (ffffffff816d4d3d)
Location: drivers/nvdimm/nd.h:71
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d5d2f)
Location: drivers/nvdimm/nd.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816dae21)
Location: drivers/nvdimm/nd.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff816dce86)
Location: drivers/nvdimm/nd.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f7a4f)
Location: drivers/nvdimm/nd.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fcdd5)
Location: drivers/nvdimm/nd.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff816ff1d6)
Location: drivers/nvdimm/nd.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8173115a)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736aa1)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff81738f73)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8175525a)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175aafb)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff8175ccc3)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81815337)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a797)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8181c67b)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81824527)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818298b7)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8182b6cb)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
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
In drivers/nvdimm/region_devs.c (ffffffff81807757)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180cac7)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff8180e9eb)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
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
In drivers/nvdimm/region_devs.c (ffffffff81891117)
Location: drivers/nvdimm/nd.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8189567a)
Location: drivers/nvdimm/nd.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff81898fcb)
Location: drivers/nvdimm/nd.h:213
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
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
In drivers/nvdimm/region_devs.c (ffffffff819da270)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819dfa31)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff819e2f5d)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
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
In drivers/nvdimm/region_devs.c (ffffffff81b55540)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5b401)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff81b5ebbd)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
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
In drivers/nvdimm/region_devs.c (ffffffff81ba8a90)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bae9b1)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff81bb2171)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
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
In drivers/nvdimm/region_devs.c (ffffffff81bfcc30)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c02d51)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff81c06661)
Location: drivers/nvdimm/nd.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010956380)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095c2e4)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffff80001095e530)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a03ee8)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0d7b4)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (c000000000a10488)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
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
In drivers/nvdimm/region_devs.c (ffffffe0005c5712)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca5fc)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffe0005cc470)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8170994a)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f1eb)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff817113b3)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dd3ca)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2c6b)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff816e4e33)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8174871a)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174dfbb)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff81750183)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81763b9a)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8176943b)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
```
```
In drivers/nvdimm/label.c (ffffffff8176b603)
Location: drivers/nvdimm/nd.h:63
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
</details>
</li>
</ul>

## Differences

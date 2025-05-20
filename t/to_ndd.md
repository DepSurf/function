# Function: <code>to_ndd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81598570)
Location: drivers/nvdimm/dimm_devs.c:221
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/label.c:del_label
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff81598570-ffffffff815985b7: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff815ee030)
Location: drivers/nvdimm/dimm_devs.c:221
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:del_label
```
**Symbols:**

```
ffffffff815ee030-ffffffff815ee077: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8161ae50)
Location: drivers/nvdimm/dimm_devs.c:230
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8161ae50-ffffffff8161ae97: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f070)
Location: drivers/nvdimm/dimm_devs.c:246
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8162f070-ffffffff8162f0a0: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816977e0)
Location: drivers/nvdimm/dimm_devs.c:253
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816977e0-ffffffff81697810: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3930)
Location: drivers/nvdimm/dimm_devs.c:255
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816d3930-ffffffff816d3958: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5050)
Location: drivers/nvdimm/dimm_devs.c:243
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816f5050-ffffffff816f5078: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8172e900)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8172e900-ffffffff8172e930: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81752b50)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81752b50-ffffffff81752b80: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81812a65)
Location: drivers/nvdimm/dimm_devs.c:230
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:init_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81811580-ffffffff818115b6: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81821cb5)
Location: drivers/nvdimm/dimm_devs.c:230
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:init_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
```
**Symbols:**

```
ffffffff81820420-ffffffff81820456: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81804fd5)
Location: drivers/nvdimm/dimm_devs.c:230
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
```
**Symbols:**

```
ffffffff81803700-ffffffff81803736: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f745)
Location: drivers/nvdimm/dimm_devs.c:230
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
```
**Symbols:**

```
ffffffff8188dca0-ffffffff8188dcd6: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d8bd5)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff819d7220-ffffffff819d7262: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b53b75)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81b51fb0-ffffffff81b51ff2: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba7065)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81ba5490-ffffffff81ba54d2: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfb315)
Location: drivers/nvdimm/dimm_devs.c:212
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81bf9710-ffffffff81bf9752: to_ndd (STB_GLOBAL)
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
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010953248)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffff800010953248-ffff800010953298: to_ndd (STB_GLOBAL)
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
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a004b0)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
c000000000a004b0-c000000000a0051c: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2c28)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffe0005c2c28-ffffffe0005c2c68: to_ndd (STB_GLOBAL)
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
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707240)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81707240-ffffffff81707270: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816dacc0)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816dacc0-ffffffff816dacf0: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746010)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81746010-ffffffff81746040: to_ndd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nvdimm_drvdata *to_ndd(struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81761450)
Location: drivers/nvdimm/dimm_devs.c:240
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:release_free_pmem
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81761450-ffffffff81761480: to_ndd (STB_GLOBAL)
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

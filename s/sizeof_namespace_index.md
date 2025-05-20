# Function: <code>sizeof_namespace_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159e9a0)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:preamble_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
Direct callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8159e9a0-ffffffff8159e9bf: sizeof_namespace_index.part.5 (STB_LOCAL)
ffffffff8159f070-ffffffff8159f097: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f67d4)
Location: drivers/nvdimm/label.c:37
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:preamble_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
Direct callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
```
**Symbols:**

```
ffffffff815f4a10-ffffffff815f4a2f: sizeof_namespace_index.part.5 (STB_LOCAL)
ffffffff815f50a0-ffffffff815f50c7: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81624740)
Location: drivers/nvdimm/label.c:37
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:preamble_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
```
**Symbols:**

```
ffffffff816226e0-ffffffff816226ff: sizeof_namespace_index.part.7 (STB_LOCAL)
ffffffff81622d60-ffffffff81622d87: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81639873)
Location: drivers/nvdimm/label.c:48
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
**Symbols:**

```
ffffffff81637300-ffffffff81637321: sizeof_namespace_index.part.9 (STB_LOCAL)
ffffffff816379a0-ffffffff816379ba: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8169fc90)
Location: drivers/nvdimm/label.c:53
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
**Symbols:**

```
ffffffff8169fc90-ffffffff8169fce7: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dbfb0)
Location: drivers/nvdimm/label.c:71
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
```
**Symbols:**

```
ffffffff816dbfb0-ffffffff816dc02f: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816fdfa0)
Location: drivers/nvdimm/label.c:71
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
```
**Symbols:**

```
ffffffff816fdfa0-ffffffff816fe01f: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff8173a5bb-ffffffff8173a5d8: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff81737ca0-ffffffff81737d14: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff8175e32b-ffffffff8175e348: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff8175b970-ffffffff8175b9e4: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181c386)
Location: drivers/nvdimm/label.c:65
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff8181dccb-ffffffff8181dce5: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff8181b1a0-ffffffff8181b214: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182b3d6)
Location: drivers/nvdimm/label.c:65
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
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
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81c15caf-ffffffff81c15cc9: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff8182a200-ffffffff8182a274: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180e6ec)
Location: drivers/nvdimm/label.c:65
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
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
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81c07a08-ffffffff81c07a22: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff8180d4e0-ffffffff8180d54f: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81898cde)
Location: drivers/nvdimm/label.c:65
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
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
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81d0b326-ffffffff81d0b340: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff81897ae0-ffffffff81897b4f: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e2be9)
Location: drivers/nvdimm/label.c:73
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_copy
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81ed3d8b-ffffffff81ed3db6: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff819e18b0-ffffffff819e1934: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5e7c1)
Location: drivers/nvdimm/label.c:73
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_copy
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81b5d510-ffffffff81b5d5b7: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb1d71)
Location: drivers/nvdimm/label.c:73
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_copy
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81bb0ad0-ffffffff81bb0b77: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c06261)
Location: drivers/nvdimm/label.c:73
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_copy
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81c04f90-ffffffff81c05037: sizeof_namespace_index (STB_GLOBAL)
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
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095d088)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffff80001095d088-ffff80001095d114: sizeof_namespace_index (STB_GLOBAL)
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
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a0e800)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
c000000000a0e800-c000000000a0e89c: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cb28a)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
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
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffe0005cb28a-ffffffe0005cb312: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81712a1b-ffffffff81712a38: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff81710060-ffffffff817100d4: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff816e649b-ffffffff816e64b8: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff816e3ae0-ffffffff816e3b54: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff817517eb-ffffffff81751808: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff8174ee30-ffffffff8174eea4: sizeof_namespace_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:65
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:holder_class_store
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:nd_label_base
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff8176cc6b-ffffffff8176cc88: sizeof_namespace_index.cold (STB_LOCAL)
ffffffff8176a2b0-ffffffff8176a324: sizeof_namespace_index (STB_GLOBAL)
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

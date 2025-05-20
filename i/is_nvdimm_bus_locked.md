# Function: <code>is_nvdimm_bus_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81597160)
Location: drivers/nvdimm/core.c:49
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81597160-ffffffff81597185: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ec0d1)
Location: drivers/nvdimm/core.c:50
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff815eb730-ffffffff815eb755: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81618cc1)
Location: drivers/nvdimm/core.c:50
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81618540-ffffffff81618569: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162ce12)
Location: drivers/nvdimm/core.c:50
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8162c3c0-ffffffff8162c3e9: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8169559f)
Location: drivers/nvdimm/core.c:50
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81695060-ffffffff81695089: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d165f)
Location: drivers/nvdimm/core.c:50
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff816d1130-ffffffff816d1159: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816f2cef)
Location: drivers/nvdimm/core.c:50
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff816f27d0-ffffffff816f27f9: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8172c2c2)
Location: drivers/nvdimm/core.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8172bd50-ffffffff8172bd79: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81750030)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81750030-ffffffff8175005a: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8180eca6)
Location: drivers/nvdimm/core.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8180e780-ffffffff8180e7aa: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8181d816)
Location: drivers/nvdimm/core.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8181d2f0-ffffffff8181d31a: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81800a86)
Location: drivers/nvdimm/core.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81800680-ffffffff818006aa: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8188ae86)
Location: drivers/nvdimm/core.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8188aa80-ffffffff8188aaaa: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff819d45bd)
Location: drivers/nvdimm/core.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff819d3e40-ffffffff819d3e6f: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81b4ee0d)
Location: drivers/nvdimm/core.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81b4e5f0-ffffffff81b4e61f: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81ba225d)
Location: drivers/nvdimm/core.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81ba1a50-ffffffff81ba1a7f: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81bf641c)
Location: drivers/nvdimm/core.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:dpa_align
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81bf5be0-ffffffff81bf5c0f: is_nvdimm_bus_locked (STB_GLOBAL)
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
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffff80001094fc70)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffff80001094fc70-ffff80001094fcbc: is_nvdimm_bus_locked (STB_GLOBAL)
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
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (c0000000009fc3b0)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
c0000000009fc3b0-c0000000009fc414: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffe0005c00fa)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffe0005c00fa-ffffffe0005c013e: is_nvdimm_bus_locked (STB_GLOBAL)
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
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81704720)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81704720-ffffffff8170474a: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d81a0)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff816d81a0-ffffffff816d81ca: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff817434f0)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff817434f0-ffffffff8174351a: is_nvdimm_bus_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8175e940)
Location: drivers/nvdimm/core.c:42
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:to_ndd
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_free_slot
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8175e940-ffffffff8175e96a: is_nvdimm_bus_locked (STB_GLOBAL)
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

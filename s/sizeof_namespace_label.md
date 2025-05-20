# Function: <code>sizeof_namespace_label</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8163978b)
Location: drivers/nvdimm/label.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff81637990-ffffffff8163799e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a1e69)
Location: drivers/nvdimm/label.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8169fc60-ffffffff8169fc6e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dcf46)
Location: drivers/nvdimm/label.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff816dbf60-ffffffff816dbf6e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816ff296)
Location: drivers/nvdimm/label.c:43
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff816fdf50-ffffffff816fdf5e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8173903e)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff81737c50-ffffffff81737c5e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175cd8e)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8175b920-ffffffff8175b92e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181c6a7)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8181b150-ffffffff8181b15e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182b6f7)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8182a1b0-ffffffff8182a1be: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180ea14)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8180d490-ffffffff8180d49e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81898ff4)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nsl_validate_blk_isetcookie
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
  - drivers/nvdimm/label.c:reap_victim
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81897a90-ffffffff81897a9e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e2f6f)
Location: drivers/nvdimm/label.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff819e1840-ffffffff819e1854: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5ebcf)
Location: drivers/nvdimm/label.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81b5d480-ffffffff81b5d494: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb218a)
Location: drivers/nvdimm/label.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81bb0a40-ffffffff81bb0a54: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c0667a)
Location: drivers/nvdimm/label.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
```
**Symbols:**

```
ffffffff81c04f00-ffffffff81c04f14: sizeof_namespace_label (STB_GLOBAL)
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095e670)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffff80001095d010-ffff80001095d038: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a10598)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
c000000000a0e7b0-c000000000a0e7c0: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cc506)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffe0005cb21e-ffffffe0005cb240: sizeof_namespace_label (STB_GLOBAL)
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8171147e)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff81710010-ffffffff8171001e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e4efe)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff816e3a90-ffffffff816e3a9e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175024e)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8174ede0-ffffffff8174edee: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176b6ce)
Location: drivers/nvdimm/label.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_nfree
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/label.c:sizeof_namespace_index
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8176a260-ffffffff8176a26e: sizeof_namespace_label (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

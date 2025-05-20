# Function: <code>import_uuid</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8156017e)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_dsk4
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8157bc6e)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_dsk4
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (0)
Location: include/linux/uuid.h:71
Inline: True
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
In block/partitions/ldm.c (ffffffff816992eb)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0148)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:71
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff819e55f6)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void import_uuid(uuid_t *dst, const __u8 *src);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff81757ba0)
Location: include/linux/uuid.h:71
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5bb6f)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff81b5eb31)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81b61496)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
**Symbols:**

```
ffffffff81757ba0-ffffffff81757bb9: import_uuid (STB_LOCAL)
ffffffff81b5d1e0-ffffffff81b5d1f0: import_uuid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void import_uuid(uuid_t *dst, const __u8 *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81795120)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bad080)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff81bb0790)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81bb47f0)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
**Symbols:**

```
ffffffff81795120-ffffffff81795139: import_uuid (STB_LOCAL)
ffffffff81bad080-ffffffff81bad099: import_uuid (STB_LOCAL)
ffffffff81bb0790-ffffffff81bb07a9: import_uuid (STB_LOCAL)
ffffffff81bb47f0-ffffffff81bb4809: import_uuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void import_uuid(uuid_t *dst, const __u8 *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d8a80)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c013c0)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff81c04c50)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c08d40)
Location: include/linux/uuid.h:81
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
**Symbols:**

```
ffffffff817d8a80-ffffffff817d8a99: import_uuid (STB_LOCAL)
ffffffff81c013c0-ffffffff81c013d9: import_uuid (STB_LOCAL)
ffffffff81c04c50-ffffffff81c04c69: import_uuid (STB_LOCAL)
ffffffff81c08d40-ffffffff81c08d59: import_uuid (STB_LOCAL)
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

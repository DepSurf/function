# Function: <code>uuid_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81694208)
Location: drivers/md/md.c:803
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f4cda)
Location: drivers/md/md.c:803
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81726490)
Location: drivers/md/md.c:833
Inline: True
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
In security/integrity/ima/ima_policy.c (ffffffff813f9756)
Location: include/linux/uuid.h:58
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff8143f980)
Location: include/linux/uuid.h:58
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
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
In security/integrity/ima/ima_policy.c (ffffffff81421be8)
Location: include/linux/uuid.h:58
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff8146be14)
Location: include/linux/uuid.h:58
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
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
In security/integrity/ima/ima_policy.c (ffffffff8145445f)
Location: include/linux/uuid.h:59
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff8149ee8b)
Location: include/linux/uuid.h:59
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
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
In security/integrity/ima/ima_policy.c (ffffffff8147119c)
Location: include/linux/uuid.h:59
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff814b9233)
Location: include/linux/uuid.h:59
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
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
In security/integrity/ima/ima_policy.c (ffffffff8149ebcf)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff814e7e2a)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
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
In security/integrity/ima/ima_policy.c (ffffffff814b972f)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff815011fa)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
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
In security/integrity/ima/ima_policy.c (ffffffff8151993c)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/partitions/ldm.c (ffffffff815610aa)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a38c3)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
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
In security/integrity/ima/ima_policy.c (ffffffff81536c1f)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/partitions/ldm.c (ffffffff8157cb9a)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/pldmfw/pldmfw.c (ffffffff8160afe0)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b28a3)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
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
In security/integrity/ima/ima_policy.c (ffffffff8153ea83)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/partitions/ldm.c (ffffffff815845f8)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/pldmfw/pldmfw.c (ffffffff815ee0c3)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895b97)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
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
In security/integrity/ima/ima_policy.c (ffffffff8159e222)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/partitions/ldm.c (ffffffff815e9dd8)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/pldmfw/pldmfw.c (ffffffff8165b183)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81929b37)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
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
In security/integrity/ima/ima_policy.c (ffffffff816432f3)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In block/partitions/ldm.c (ffffffff81699728)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/pldmfw/pldmfw.c (ffffffff81774012)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e015a)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:61
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff819e5611)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7ff96)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
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
In security/integrity/ima/ima_policy.c (ffffffff816fb5b3)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In block/partitions/ldm.c (ffffffff81758b38)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/pldmfw/pldmfw.c (ffffffff818a4af2)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5bb81)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:61
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81b614b1)
Location: include/linux/uuid.h:61
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uuid_equal(const uuid_t *u1, const uuid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81735688)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In block/partitions/ldm.c (ffffffff81796035)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
Direct callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/pldmfw/pldmfw.c (ffffffff818e76f2)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81baf13c)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:71
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81bb4a6b)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
**Symbols:**

```
ffffffff81794880-ffffffff817948b5: uuid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uuid_equal(const uuid_t *u1, const uuid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81776168)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/partitions/ldm.c (ffffffff817d99a5)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
Direct callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In lib/pldmfw/pldmfw.c (ffffffff8192e732)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c0350c)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:71
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c08feb)
Location: include/linux/uuid.h:71
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
**Symbols:**

```
ffffffff817d81e0-ffffffff817d8215: uuid_equal (STB_LOCAL)
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
In security/integrity/ima/ima_policy.c (ffff8000105b16e8)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffff8000106033d0)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c0760cc4)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (c07ae95c)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
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
In security/integrity/ima/ima_policy.c (c00000000073163c)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (c00000000079ec00)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
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
In security/integrity/ima/ima_policy.c (ffffffe0003f8e90)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffe00043e960)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
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
In security/integrity/ima/ima_policy.c (ffffffff814b1d0f)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff814f97da)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In drivers/nvme/host/core.c (ffffffff81746cc8)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:wwid_show
  - drivers/nvme/host/core.c:nvme_ns_ids_equal
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
In security/integrity/ima/ima_policy.c (ffffffff814a272f)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff814e9cea)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In drivers/nvme/host/core.c (ffffffff81728948)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:wwid_show
  - drivers/nvme/host/core.c:nvme_ns_ids_equal
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
In security/integrity/ima/ima_policy.c (ffffffff814add9f)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff814f586a)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
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
In security/integrity/ima/ima_policy.c (ffffffff814c67ef)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In block/partitions/ldm.c (ffffffff8150e8ca)
Location: include/linux/uuid.h:51
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_validate_privheads
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

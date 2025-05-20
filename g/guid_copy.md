# Function: <code>guid_copy</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:49
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:49
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
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
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
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
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void guid_copy(guid_t *dst, const guid_t *src);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81cf0ffb)
Location: include/linux/uuid.h:41
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
**Symbols:**

```
ffffffff81cf0ffb-ffffffff81cf100a: guid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void guid_copy(guid_t *dst, const guid_t *src);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81eb8efc)
Location: include/linux/uuid.h:41
Inline: True
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/nvdimm/label.c (ffffffff819e2ed1)
Location: include/linux/uuid.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
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
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff81eb8efc-ffffffff81eb8f15: guid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void guid_copy(guid_t *dst, const guid_t *src);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff8197a080)
Location: include/linux/uuid.h:41
Inline: True
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/nvdimm/label.c (ffffffff81b5d230)
Location: include/linux/uuid.h:41
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8197a080-ffffffff8197a099: guid_copy (STB_LOCAL)
ffffffff81b5d1e0-ffffffff81b5d1f0: guid_copy.part.0 (STB_LOCAL)
ffffffff81b5d230-ffffffff81b5d249: guid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void guid_copy(guid_t *dst, const guid_t *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff819c0b10)
Location: include/linux/uuid.h:51
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/nvdimm/label.c (ffffffff81bb07f0)
Location: include/linux/uuid.h:51
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff819c0b10-ffffffff819c0b29: guid_copy (STB_LOCAL)
ffffffff81bb07f0-ffffffff81bb0809: guid_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void guid_copy(guid_t *dst, const guid_t *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81a0b500)
Location: include/linux/uuid.h:51
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/nvdimm/label.c (ffffffff81c04cb0)
Location: include/linux/uuid.h:51
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81a0b500-ffffffff81a0b519: guid_copy (STB_LOCAL)
ffffffff81c04cb0-ffffffff81c04cc9: guid_copy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a118a0)
Location: include/linux/uuid.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005ccccc)
Location: include/linux/uuid.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
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
In drivers/acpi/nfit/core.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
```
In drivers/hv/vmbus_drv.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: include/linux/uuid.h:41
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

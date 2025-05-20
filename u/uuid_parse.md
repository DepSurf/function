# Function: <code>uuid_parse</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81464420)
Location: lib/uuid.c:127
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81464420-ffffffff81464432: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814903a0)
Location: lib/uuid.c:127
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff814903a0-ffffffff814903b2: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814c5190)
Location: lib/uuid.c:127
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff814c5190-ffffffff814c51b2: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff814d9890)
Location: lib/uuid.c:127
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff814d9890-ffffffff814d98b8: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81505600)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff81505600-ffffffff81505636: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815235e0)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff815235e0-ffffffff81523616: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81586ba0)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_privhead
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
**Symbols:**

```
ffffffff81586ba0-ffffffff81586bc8: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815a3e90)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_privhead
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
**Symbols:**

```
ffffffff815a3e90-ffffffff815a3eb8: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815aada0)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_validate_privheads
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
**Symbols:**

```
ffffffff815aada0-ffffffff815aadc8: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81614080)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_validate_privheads
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match
```
**Symbols:**

```
ffffffff81614080-ffffffff816140a8: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff816e0960)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_validate_privheads
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match
```
**Symbols:**

```
ffffffff816e0960-ffffffff816e09ae: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff817d0d00)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_validate_privheads
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
```
**Symbols:**

```
ffffffff817d0d00-ffffffff817d0d3e: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8180f960)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_validate_privheads
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
```
**Symbols:**

```
ffffffff8180f960-ffffffff8180f99e: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff818555e0)
Location: lib/uuid.c:129
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_validate_privheads
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
  - drivers/nvdimm/label.c:nd_label_init
```
**Symbols:**

```
ffffffff818555e0-ffffffff8185561e: uuid_parse (STB_GLOBAL)
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
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffff80001062d418)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_privhead
```
**Symbols:**

```
ffff80001062d418-ffff80001062d45c: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (c07d3f4c)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
c07d3f4c-c07d3f8c: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (c0000000007d04d0)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
c0000000007d04d0-c0000000007d054c: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffe00045d2a2)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffe00045d2a2-ffffffe00045d2e0: uuid_parse (STB_GLOBAL)
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
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8151bbc0)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff8151bbc0-ffffffff8151bbf6: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff8150beb0)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff8150beb0-ffffffff8150bee6: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff81517c50)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff81517c50-ffffffff81517c86: uuid_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uuid_parse(const char *uuid, uuid_t *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/uuid.c (ffffffff815313f0)
Location: lib/uuid.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff815313f0-ffffffff81531426: uuid_parse (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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

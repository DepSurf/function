# Function: <code>domain_context_mapping_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81538740)
Location: drivers/iommu/intel-iommu.c:1939
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81538740-ffffffff81538bf2: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158d220)
Location: drivers/iommu/intel-iommu.c:1983
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff8158d220-ffffffff8158d6a8: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bab20)
Location: drivers/iommu/intel-iommu.c:2007
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff815bab20-ffffffff815bb00e: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d0790)
Location: drivers/iommu/intel-iommu.c:2012
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff815d0790-ffffffff815d0c98: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81637580)
Location: drivers/iommu/intel-iommu.c:2011
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff81637580-ffffffff81637a9c: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81672780)
Location: drivers/iommu/intel-iommu.c:2039
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff81672780-ffffffff81672ca8: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816915f0)
Location: drivers/iommu/intel-iommu.c:1975
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff816915f0-ffffffff81691aa0: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1962
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff816c9590-ffffffff816c9a7e: domain_context_mapping_one (STB_LOCAL)
ffffffff816cc427-ffffffff816cc45d: domain_context_mapping_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ec690)
Location: drivers/iommu/intel-iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff816ec690-ffffffff816ecb8c: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a4780)
Location: drivers/iommu/intel/iommu.c:1988
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff817a4780-ffffffff817a4c6d: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b1c10)
Location: drivers/iommu/intel/iommu.c:2046
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff817b1c10-ffffffff817b20fd: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817949f0)
Location: drivers/iommu/intel/iommu.c:2052
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff817949f0-ffffffff81794e9d: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181c820)
Location: drivers/iommu/intel/iommu.c:2044
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff8181c820-ffffffff8181ccf5: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195ce60)
Location: drivers/iommu/intel/iommu.c:1936
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff8195ce60-ffffffff8195d313: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac49c0)
Location: drivers/iommu/intel/iommu.c:1921
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff81ac49c0-ffffffff81ac4e8a: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b113a0)
Location: drivers/iommu/intel/iommu.c:1889
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff81b113a0-ffffffff81b1181a: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b65760)
Location: drivers/iommu/intel/iommu.c:1806
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff81b65760-ffffffff81b65bdd: domain_context_mapping_one (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b1fc0)
Location: drivers/iommu/intel-iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff816b1fc0-ffffffff816b24bc: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168fac0)
Location: drivers/iommu/intel-iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff8168fac0-ffffffff8168ffbc: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e0350)
Location: drivers/iommu/intel-iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff816e0350-ffffffff816e084c: domain_context_mapping_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int domain_context_mapping_one(struct dmar_domain *domain, struct intel_iommu *iommu, struct pasid_table *table, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fa960)
Location: drivers/iommu/intel-iommu.c:1973
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_cb
```
**Symbols:**

```
ffffffff816fa960-ffffffff816fae5a: domain_context_mapping_one (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pasid_table *table</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, iommu, bus, devfn</code> ➡️ <code>domain, iommu, table, bus, devfn</code>
</li>
</ul>
</details>
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

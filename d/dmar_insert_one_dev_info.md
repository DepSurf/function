# Function: <code>dmar_insert_one_dev_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81539b30)
Location: drivers/iommu/intel-iommu.c:2316
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff81539b30-ffffffff8153a00f: dmar_insert_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158e5e0)
Location: drivers/iommu/intel-iommu.c:2360
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff8158e5e0-ffffffff8158eab2: dmar_insert_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bc100)
Location: drivers/iommu/intel-iommu.c:2403
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
```
**Symbols:**

```
ffffffff815bc100-ffffffff815bc5d2: dmar_insert_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d1d30)
Location: drivers/iommu/intel-iommu.c:2411
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
```
**Symbols:**

```
ffffffff815d1d30-ffffffff815d2221: dmar_insert_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81638b10)
Location: drivers/iommu/intel-iommu.c:2435
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
```
**Symbols:**

```
ffffffff81638b10-ffffffff81639001: dmar_insert_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2492
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
```
**Symbols:**

```
ffffffff81673df0-ffffffff8167426f: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff8167574a-ffffffff8167579b: dmar_insert_one_dev_info.cold.95 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2461
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
```
**Symbols:**

```
ffffffff81692380-ffffffff81692898: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff81693be7-ffffffff81693c9b: dmar_insert_one_dev_info.cold.100 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2450
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff816ca2f0-ffffffff816ca739: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff816cc4b8-ffffffff816cc4ec: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2461
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff816ed2c0-ffffffff816ed709: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff816efd03-ffffffff816efd37: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2516
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff817a5360-ffffffff817a585b: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff817a73e2-ffffffff817a7413: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2537
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff817b27d0-ffffffff817b2cee: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff81c0cc43-ffffffff81c0cc74: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2577
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff817956c0-ffffffff81795bde: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff81bfe38e-ffffffff81bfe3bf: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2567
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff8181d540-ffffffff8181daa6: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff81d001db-ffffffff81d00238: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2461
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff816b2a30-ffffffff816b2e79: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff816b54e9-ffffffff816b551d: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2461
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff816906f0-ffffffff81690b39: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff81693133-ffffffff81693167: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2461
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff816e0f80-ffffffff816e13c9: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff816e39c3-ffffffff816e39f7: dmar_insert_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dmar_domain *dmar_insert_one_dev_info(struct intel_iommu *iommu, int bus, int devfn, struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2461
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
```
**Symbols:**

```
ffffffff816fb590-ffffffff816fb9dc: dmar_insert_one_dev_info (STB_LOCAL)
ffffffff816fe06f-ffffffff816fe0a3: dmar_insert_one_dev_info.cold (STB_LOCAL)
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

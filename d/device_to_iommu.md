# Function: <code>device_to_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535490)
Location: drivers/iommu/intel-iommu.c:875
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
```
**Symbols:**

```
ffffffff81535490-ffffffff81535633: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81589ec0)
Location: drivers/iommu/intel-iommu.c:882
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81589ec0-ffffffff8158a03a: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b7570)
Location: drivers/iommu/intel-iommu.c:883
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff815b7570-ffffffff815b771e: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cd3e0)
Location: drivers/iommu/intel-iommu.c:888
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff815cd3e0-ffffffff815cd5c9: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816341e0)
Location: drivers/iommu/intel-iommu.c:861
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816341e0-ffffffff816343eb: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8166f6f0)
Location: drivers/iommu/intel-iommu.c:863
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8166f6f0-ffffffff8166f905: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168dc50)
Location: drivers/iommu/intel-iommu.c:739
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:set_domain_for_dev
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8168dc50-ffffffff8168de65: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c65b0)
Location: drivers/iommu/intel-iommu.c:751
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816c65b0-ffffffff816c67aa: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e9520)
Location: drivers/iommu/intel-iommu.c:762
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816e9520-ffffffff816e971a: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a02e0)
Location: drivers/iommu/intel/iommu.c:782
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817a02e0-ffffffff817a04ea: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:865
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81c0cad0-ffffffff81c0cafc: device_to_iommu.cold (STB_LOCAL)
ffffffff817b0f60-ffffffff817b1252: device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:881
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81bfe252-ffffffff81bfe27e: device_to_iommu.cold (STB_LOCAL)
ffffffff81793af0-ffffffff81793ddf: device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:887
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_bind
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81cfffb8-ffffffff81cffff8: device_to_iommu.cold (STB_LOCAL)
ffffffff8181b990-ffffffff8181bc8b: device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:734
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_bind
```
**Symbols:**

```
ffffffff81ec86f2-ffffffff81ec8732: device_to_iommu.cold (STB_LOCAL)
ffffffff8195c720-ffffffff8195ca45: device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:710
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/svm.c:intel_svm_page_response
```
**Symbols:**

```
ffffffff82097a6f-ffffffff82097a83: device_to_iommu.cold (STB_LOCAL)
ffffffff81ac4200-ffffffff81ac4546: device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:710
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/svm.c:intel_svm_page_response
```
**Symbols:**

```
ffffffff821189dc-ffffffff821189f0: device_to_iommu.cold (STB_LOCAL)
ffffffff81b10bc0-ffffffff81b10ee7: device_to_iommu (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816af000)
Location: drivers/iommu/intel-iommu.c:762
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816af000-ffffffff816af1fa: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168c960)
Location: drivers/iommu/intel-iommu.c:762
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8168c960-ffffffff8168cb48: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dd1e0)
Location: drivers/iommu/intel-iommu.c:762
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816dd1e0-ffffffff816dd3da: device_to_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct intel_iommu *device_to_iommu(struct device *dev, u8 *bus, u8 *devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f76d0)
Location: drivers/iommu/intel-iommu.c:762
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat
  - drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_add_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816f76d0-ffffffff816f78d7: device_to_iommu (STB_LOCAL)
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

# Function: <code>__dmar_remove_one_dev_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81538e80)
Location: drivers/iommu/intel-iommu.c:4687
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81538e80-ffffffff8153909d: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158d940)
Location: drivers/iommu/intel-iommu.c:4825
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff8158d940-ffffffff8158db65: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bb0e0)
Location: drivers/iommu/intel-iommu.c:4918
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff815bb0e0-ffffffff815bb305: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d0d60)
Location: drivers/iommu/intel-iommu.c:4952
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff815d0d60-ffffffff815d0f66: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81637b60)
Location: drivers/iommu/intel-iommu.c:4867
Inline: False
```
**Symbols:**

```
ffffffff81637b60-ffffffff81637d67: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81672ec0)
Location: drivers/iommu/intel-iommu.c:4909
Inline: False
```
**Symbols:**

```
ffffffff81672ec0-ffffffff816730ce: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168fb70)
Location: drivers/iommu/intel-iommu.c:4959
Inline: False
```
**Symbols:**

```
ffffffff8168fb70-ffffffff8168fde9: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4813
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816c77a0-ffffffff816c79e4: __dmar_remove_one_dev_info (STB_LOCAL)
ffffffff816cbe2e-ffffffff816cbe41: __dmar_remove_one_dev_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ea710)
Location: drivers/iommu/intel-iommu.c:5096
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816ea710-ffffffff816ea95f: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a1fd0)
Location: drivers/iommu/intel/iommu.c:4983
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff817a1fd0-ffffffff817a221c: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b0190)
Location: drivers/iommu/intel/iommu.c:4373
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff817b0190-ffffffff817b03e0: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791f90)
Location: drivers/iommu/intel/iommu.c:4472
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81791f90-ffffffff817921c9: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81819850)
Location: drivers/iommu/intel/iommu.c:4460
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81819850-ffffffff81819a89: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195b8a0)
Location: drivers/iommu/intel/iommu.c:4198
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff8195b8a0-ffffffff8195bbc3: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b01f0)
Location: drivers/iommu/intel-iommu.c:5096
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816b01f0-ffffffff816b043f: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168db40)
Location: drivers/iommu/intel-iommu.c:5096
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff8168db40-ffffffff8168dd8f: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816de3d0)
Location: drivers/iommu/intel-iommu.c:5096
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816de3d0-ffffffff816de61f: __dmar_remove_one_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dmar_remove_one_dev_info(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f8af0)
Location: drivers/iommu/intel-iommu.c:5096
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816f8af0-ffffffff816f8d3f: __dmar_remove_one_dev_info (STB_LOCAL)
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

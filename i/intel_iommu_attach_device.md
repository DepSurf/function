# Function: <code>intel_iommu_attach_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153a450)
Location: drivers/iommu/intel-iommu.c:4784
Inline: False
```
**Symbols:**

```
ffffffff8153a450-ffffffff8153a67f: intel_iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158ef50)
Location: drivers/iommu/intel-iommu.c:4922
Inline: False
```
**Symbols:**

```
ffffffff8158ef50-ffffffff8158f178: intel_iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bca70)
Location: drivers/iommu/intel-iommu.c:5015
Inline: False
```
**Symbols:**

```
ffffffff815bca70-ffffffff815bcc98: intel_iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d22c0)
Location: drivers/iommu/intel-iommu.c:5049
Inline: False
```
**Symbols:**

```
ffffffff815d22c0-ffffffff815d24e8: intel_iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816390a0)
Location: drivers/iommu/intel-iommu.c:4963
Inline: False
```
**Symbols:**

```
ffffffff816390a0-ffffffff816392c8: intel_iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5005
Inline: False
```
**Symbols:**

```
ffffffff81674300-ffffffff81674508: intel_iommu_attach_device (STB_LOCAL)
ffffffff8167579b-ffffffff816757bb: intel_iommu_attach_device.cold.96 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5060
Inline: False
```
**Symbols:**

```
ffffffff81692930-ffffffff81692b38: intel_iommu_attach_device (STB_LOCAL)
ffffffff81693c9b-ffffffff81693cbb: intel_iommu_attach_device.cold.101 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5108
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816ca7d0-ffffffff816ca8ec: intel_iommu_attach_device (STB_LOCAL)
ffffffff816cc4ec-ffffffff816cc503: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5392
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816ed7a0-ffffffff816ed8bc: intel_iommu_attach_device (STB_LOCAL)
ffffffff816efd37-ffffffff816efd4e: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5282
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:intel_alloc_coherent
  - drivers/iommu/intel/iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff817a5860-ffffffff817a5a5f: intel_iommu_attach_device (STB_LOCAL)
ffffffff817a7413-ffffffff817a742b: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4703
Inline: False
```
**Symbols:**

```
ffffffff817b2cf0-ffffffff817b2ed4: intel_iommu_attach_device (STB_LOCAL)
ffffffff81c0cc74-ffffffff81c0cc8c: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4803
Inline: False
```
**Symbols:**

```
ffffffff81795be0-ffffffff81795e55: intel_iommu_attach_device (STB_LOCAL)
ffffffff81bfe3bf-ffffffff81bfe3d7: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4794
Inline: False
```
**Symbols:**

```
ffffffff8181dab0-ffffffff8181dd25: intel_iommu_attach_device (STB_LOCAL)
ffffffff81d00238-ffffffff81d00250: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4348
Inline: False
```
**Symbols:**

```
ffffffff8195d7d0-ffffffff8195dabe: intel_iommu_attach_device (STB_LOCAL)
ffffffff81ec87ce-ffffffff81ec8826: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4262
Inline: False
```
**Symbols:**

```
ffffffff81ac51d0-ffffffff81ac53f6: intel_iommu_attach_device (STB_LOCAL)
ffffffff82097a83-ffffffff82097aa4: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4151
Inline: False
```
**Symbols:**

```
ffffffff81b11c40-ffffffff81b11e66: intel_iommu_attach_device (STB_LOCAL)
ffffffff821189f0-ffffffff82118a11: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b67830)
Location: drivers/iommu/intel/iommu.c:4049
Inline: True
```
**Symbols:**

```
ffffffff81b67830-ffffffff81b6788a: intel_iommu_attach_device (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5392
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816b2f10-ffffffff816b302c: intel_iommu_attach_device (STB_LOCAL)
ffffffff816b551d-ffffffff816b5534: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5392
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff81690bd0-ffffffff81690cec: intel_iommu_attach_device (STB_LOCAL)
ffffffff81693167-ffffffff8169317e: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5392
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816e1460-ffffffff816e157c: intel_iommu_attach_device (STB_LOCAL)
ffffffff816e39f7-ffffffff816e3a0e: intel_iommu_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5392
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816fba70-ffffffff816fbb8c: intel_iommu_attach_device (STB_LOCAL)
ffffffff816fe0a3-ffffffff816fe0ba: intel_iommu_attach_device.cold (STB_LOCAL)
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

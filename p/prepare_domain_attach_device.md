# Function: <code>prepare_domain_attach_device</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5065
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff816c67b0-ffffffff816c68b2: prepare_domain_attach_device (STB_LOCAL)
ffffffff816cbd91-ffffffff816cbdb1: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5349
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff816e9720-ffffffff816e9822: prepare_domain_attach_device (STB_LOCAL)
ffffffff816ef6ba-ffffffff816ef6da: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5239
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff817a0570-ffffffff817a0673: prepare_domain_attach_device (STB_LOCAL)
ffffffff817a6b62-ffffffff817a6b82: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4661
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff817b16c0-ffffffff817b1794: prepare_domain_attach_device (STB_LOCAL)
ffffffff81c0cb7d-ffffffff81c0cb9d: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4761
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff81794250-ffffffff81794323: prepare_domain_attach_device (STB_LOCAL)
ffffffff81bfe2f7-ffffffff81bfe317: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4746
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff8181c150-ffffffff8181c251: prepare_domain_attach_device (STB_LOCAL)
ffffffff81d000e9-ffffffff81d00145: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195d849)
Location: drivers/iommu/intel/iommu.c:4304
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac5214)
Location: drivers/iommu/intel/iommu.c:4222
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b11c84)
Location: drivers/iommu/intel/iommu.c:4111
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4009
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
```
**Symbols:**

```
ffffffff821f6767-ffffffff821f6788: prepare_domain_attach_device.cold (STB_LOCAL)
ffffffff81b674c0-ffffffff81b675e3: prepare_domain_attach_device (STB_GLOBAL)
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
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5349
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff816af200-ffffffff816af302: prepare_domain_attach_device (STB_LOCAL)
ffffffff816b4eaa-ffffffff816b4eca: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5349
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff8168cb50-ffffffff8168cc52: prepare_domain_attach_device (STB_LOCAL)
ffffffff81692aea-ffffffff81692b0a: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5349
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff816dd3e0-ffffffff816dd4e2: prepare_domain_attach_device (STB_LOCAL)
ffffffff816e337a-ffffffff816e339a: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int prepare_domain_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5349
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
**Symbols:**

```
ffffffff816f78e0-ffffffff816f79e2: prepare_domain_attach_device (STB_LOCAL)
ffffffff816fda0a-ffffffff816fda2a: prepare_domain_attach_device.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

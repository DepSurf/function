# Function: <code>intel_iommu_aux_attach_device</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c7ec9)
Location: drivers/iommu/intel-iommu.c:5138
Inline: True
```
**Symbols:**

```
ffffffff816c7e50-ffffffff816c8044: intel_iommu_aux_attach_device (STB_LOCAL)
ffffffff816cbe82-ffffffff816cbeac: intel_iommu_aux_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eae79)
Location: drivers/iommu/intel-iommu.c:5422
Inline: True
```
**Symbols:**

```
ffffffff816eae00-ffffffff816eaffb: intel_iommu_aux_attach_device (STB_LOCAL)
ffffffff816ef757-ffffffff816ef76e: intel_iommu_aux_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a3770)
Location: drivers/iommu/intel/iommu.c:5312
Inline: True
```
**Symbols:**

```
ffffffff817a3770-ffffffff817a37d1: intel_iommu_aux_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b1930)
Location: drivers/iommu/intel/iommu.c:4733
Inline: True
```
**Symbols:**

```
ffffffff817b1930-ffffffff817b19a4: intel_iommu_aux_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81794670)
Location: drivers/iommu/intel/iommu.c:4833
Inline: True
```
**Symbols:**

```
ffffffff81794670-ffffffff817946e4: intel_iommu_aux_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181c5a0)
Location: drivers/iommu/intel/iommu.c:4824
Inline: True
```
**Symbols:**

```
ffffffff8181c5a0-ffffffff8181c614: intel_iommu_aux_attach_device (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0959)
Location: drivers/iommu/intel-iommu.c:5422
Inline: True
```
**Symbols:**

```
ffffffff816b08e0-ffffffff816b0adb: intel_iommu_aux_attach_device (STB_LOCAL)
ffffffff816b4f47-ffffffff816b4f5e: intel_iommu_aux_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e2a9)
Location: drivers/iommu/intel-iommu.c:5422
Inline: True
```
**Symbols:**

```
ffffffff8168e230-ffffffff8168e42b: intel_iommu_aux_attach_device (STB_LOCAL)
ffffffff81692b87-ffffffff81692b9e: intel_iommu_aux_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816deb39)
Location: drivers/iommu/intel-iommu.c:5422
Inline: True
```
**Symbols:**

```
ffffffff816deac0-ffffffff816decbb: intel_iommu_aux_attach_device (STB_LOCAL)
ffffffff816e3417-ffffffff816e342e: intel_iommu_aux_attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int intel_iommu_aux_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f9149)
Location: drivers/iommu/intel-iommu.c:5422
Inline: True
```
**Symbols:**

```
ffffffff816f90d0-ffffffff816f92c7: intel_iommu_aux_attach_device (STB_LOCAL)
ffffffff816fdaa7-ffffffff816fdabe: intel_iommu_aux_attach_device.cold (STB_LOCAL)
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

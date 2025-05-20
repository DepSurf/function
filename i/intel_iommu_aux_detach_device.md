# Function: <code>intel_iommu_aux_detach_device</code>

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
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5159
Inline: False
```
**Symbols:**

```
ffffffff816c7d40-ffffffff816c7e42: intel_iommu_aux_detach_device (STB_LOCAL)
ffffffff816cbe6f-ffffffff816cbe82: intel_iommu_aux_detach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eacf0)
Location: drivers/iommu/intel-iommu.c:5443
Inline: False
```
**Symbols:**

```
ffffffff816eacf0-ffffffff816eadf6: intel_iommu_aux_detach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a2e60)
Location: drivers/iommu/intel/iommu.c:5333
Inline: False
```
**Symbols:**

```
ffffffff817a2e60-ffffffff817a2f43: intel_iommu_aux_detach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b0740)
Location: drivers/iommu/intel/iommu.c:4754
Inline: False
```
**Symbols:**

```
ffffffff817b0740-ffffffff817b0757: intel_iommu_aux_detach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81793370)
Location: drivers/iommu/intel/iommu.c:4854
Inline: False
```
**Symbols:**

```
ffffffff81793370-ffffffff8179347a: intel_iommu_aux_detach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181b190)
Location: drivers/iommu/intel/iommu.c:4845
Inline: False
```
**Symbols:**

```
ffffffff8181b190-ffffffff8181b29a: intel_iommu_aux_detach_device (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b07d0)
Location: drivers/iommu/intel-iommu.c:5443
Inline: False
```
**Symbols:**

```
ffffffff816b07d0-ffffffff816b08d6: intel_iommu_aux_detach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e120)
Location: drivers/iommu/intel-iommu.c:5443
Inline: False
```
**Symbols:**

```
ffffffff8168e120-ffffffff8168e226: intel_iommu_aux_detach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816de9b0)
Location: drivers/iommu/intel-iommu.c:5443
Inline: False
```
**Symbols:**

```
ffffffff816de9b0-ffffffff816deab6: intel_iommu_aux_detach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_iommu_aux_detach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f89e0)
Location: drivers/iommu/intel-iommu.c:5443
Inline: False
```
**Symbols:**

```
ffffffff816f89e0-ffffffff816f8ae4: intel_iommu_aux_detach_device (STB_LOCAL)
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

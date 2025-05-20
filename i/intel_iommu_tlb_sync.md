# Function: <code>intel_iommu_tlb_sync</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_iommu_tlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af110)
Location: drivers/iommu/intel/iommu.c:5006
Inline: False
```
**Symbols:**

```
ffffffff817af110-ffffffff817af1fd: intel_iommu_tlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_iommu_tlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791af0)
Location: drivers/iommu/intel/iommu.c:5104
Inline: False
```
**Symbols:**

```
ffffffff81791af0-ffffffff81791bdd: intel_iommu_tlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_iommu_tlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818194d0)
Location: drivers/iommu/intel/iommu.c:5128
Inline: False
```
**Symbols:**

```
ffffffff818194d0-ffffffff818195ec: intel_iommu_tlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_iommu_tlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff819597f0)
Location: drivers/iommu/intel/iommu.c:4477
Inline: False
```
**Symbols:**

```
ffffffff819597f0-ffffffff819598f5: intel_iommu_tlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_iommu_tlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac1120)
Location: drivers/iommu/intel/iommu.c:4386
Inline: False
```
**Symbols:**

```
ffffffff81ac1120-ffffffff81ac122a: intel_iommu_tlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_iommu_tlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0d9b0)
Location: drivers/iommu/intel/iommu.c:4277
Inline: False
```
**Symbols:**

```
ffffffff81b0d9b0-ffffffff81b0dab5: intel_iommu_tlb_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_iommu_tlb_sync(struct iommu_domain *domain, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b62300)
Location: drivers/iommu/intel/iommu.c:4169
Inline: False
```
**Symbols:**

```
ffffffff81b62300-ffffffff81b62436: intel_iommu_tlb_sync (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

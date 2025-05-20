# Function: <code>amd_iommu_update_and_flush_device_table</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_update_and_flush_device_table(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8178a7de)
Location: drivers/iommu/amd/iommu.c:1759
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff8178a790-ffffffff8178a7cb: amd_iommu_update_and_flush_device_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_update_and_flush_device_table(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81811abe)
Location: drivers/iommu/amd/iommu.c:1803
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff81811a70-ffffffff81811aab: amd_iommu_update_and_flush_device_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_update_and_flush_device_table(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81952860)
Location: drivers/iommu/amd/iommu.c:1825
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff81952800-ffffffff81952843: amd_iommu_update_and_flush_device_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_update_and_flush_device_table(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab7aa0)
Location: drivers/iommu/amd/iommu.c:1949
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff81ab7a30-ffffffff81ab7a73: amd_iommu_update_and_flush_device_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_update_and_flush_device_table(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b03cee)
Location: drivers/iommu/amd/iommu.c:1974
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff81b03c80-ffffffff81b03cc3: amd_iommu_update_and_flush_device_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_update_and_flush_device_table(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b575a5)
Location: drivers/iommu/amd/iommu.c:2022
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81b57910-ffffffff81b57953: amd_iommu_update_and_flush_device_table (STB_GLOBAL)
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

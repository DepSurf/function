# Function: <code>iommu_enable_irtcachedis</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_enable_irtcachedis(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b053ba)
Location: drivers/iommu/amd/init.c:2722
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81b05380-ffffffff81b05443: iommu_enable_irtcachedis (STB_LOCAL)
ffffffff82118010-ffffffff82118039: iommu_enable_irtcachedis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_enable_irtcachedis(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58f9a)
Location: drivers/iommu/amd/init.c:2742
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81b58f60-ffffffff81b59023: iommu_enable_irtcachedis (STB_LOCAL)
ffffffff821f5c1c-ffffffff821f5c45: iommu_enable_irtcachedis.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

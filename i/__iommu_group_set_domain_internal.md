# Function: <code>__iommu_group_set_domain_internal</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
int __iommu_group_set_domain_internal(struct iommu_group *group, struct iommu_domain *new_domain, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1e370)
Location: drivers/iommu/iommu.c:2161
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_release_dma_ownership
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_detach_group
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff81b1e370-ffffffff81b1e4e4: __iommu_group_set_domain_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __iommu_group_set_domain_internal(struct iommu_group *group, struct iommu_domain *new_domain, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b7693f)
Location: drivers/iommu/iommu.c:2467
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_release_dma_ownership
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_detach_group
  - drivers/iommu/iommu.c:iommu_detach_device
Direct callers:
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_group_replace_domain
  - drivers/iommu/iommu.c:__iommu_attach_group
```
**Symbols:**

```
ffffffff81b74c00-ffffffff81b74cf7: __iommu_group_set_domain_internal (STB_LOCAL)
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

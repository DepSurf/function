# Function: <code>ioasid_put</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ioasid_put(ioasid_t ioasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:376
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_remove_dev
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff81c0d769-ffffffff81c0d780: ioasid_put.cold (STB_LOCAL)
ffffffff817bf8f0-ffffffff817bf9bb: ioasid_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ioasid_put(ioasid_t ioasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:376
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff81bffad2-ffffffff81bffae9: ioasid_put.cold (STB_LOCAL)
ffffffff817a2b10-ffffffff817a2bdb: ioasid_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ioasid_put(ioasid_t ioasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:376
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/iommu-sva-lib.c:iommu_sva_free_pasid
```
**Symbols:**

```
ffffffff81d01fad-ffffffff81d01fc4: ioasid_put.cold (STB_LOCAL)
ffffffff8182be50-ffffffff8182bf1b: ioasid_put (STB_GLOBAL)
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
</ul>

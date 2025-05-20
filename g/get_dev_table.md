# Function: <code>get_dev_table</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dev_table_entry *get_dev_table(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab55ef)
Location: drivers/iommu/amd/iommu.c:122
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:clone_alias
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_apply_erratum_63
  - drivers/iommu/amd/init.c:amd_iommu_apply_erratum_63
  - drivers/iommu/amd/init.c:amd_iommu_apply_erratum_63
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
**Symbols:**

```
ffffffff81ab7330-ffffffff81ab7357: get_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dev_table_entry *get_dev_table(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b01811)
Location: drivers/iommu/amd/iommu.c:122
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:clone_alias
Direct callers:
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
**Symbols:**

```
ffffffff81b03680-ffffffff81b036a7: get_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dev_table_entry *get_dev_table(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b5721b)
Location: drivers/iommu/amd/iommu.c:125
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_set_dirty_tracking
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/iommu.c:clone_alias
Direct callers:
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
**Symbols:**

```
ffffffff81b55f50-ffffffff81b55f77: get_dev_table (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

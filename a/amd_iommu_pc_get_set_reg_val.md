# Function: <code>amd_iommu_pc_get_set_reg_val</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int amd_iommu_pc_get_set_reg_val(u16 devid, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815326e0)
Location: drivers/iommu/amd_iommu_init.c:2352
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff815326e0-ffffffff81532720: amd_iommu_pc_get_set_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int amd_iommu_pc_get_set_reg_val(u16 devid, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81586ec0)
Location: drivers/iommu/amd_iommu_init.c:2613
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff81586ec0-ffffffff81586f00: amd_iommu_pc_get_set_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_iommu_pc_get_set_reg_val(u16 devid, u8 bank, u8 cntr, u8 fxn, u64 *value, bool is_write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4610)
Location: drivers/iommu/amd_iommu_init.c:2785
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff815b4610-ffffffff815b4650: amd_iommu_pc_get_set_reg_val (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>

# Function: <code>search_dev_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iommu_dev_data *search_dev_data(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152d5b0)
Location: drivers/iommu/amd_iommu.c:146
Inline: False
```
**Symbols:**

```
ffffffff8152d5b0-ffffffff8152d620: search_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct iommu_dev_data *search_dev_data(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581110)
Location: drivers/iommu/amd_iommu.c:258
Inline: False
```
**Symbols:**

```
ffffffff81581110-ffffffff81581180: search_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct iommu_dev_data *search_dev_data(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815adce0)
Location: drivers/iommu/amd_iommu.c:259
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_set_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_prepare
```
**Symbols:**

```
ffffffff815adce0-ffffffff815add50: search_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct iommu_dev_data *search_dev_data(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3960)
Location: drivers/iommu/amd_iommu.c:290
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_set_affinity
```
**Symbols:**

```
ffffffff815c3960-ffffffff815c39d0: search_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct iommu_dev_data *search_dev_data(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162a640)
Location: drivers/iommu/amd_iommu.c:223
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_set_affinity
```
**Symbols:**

```
ffffffff8162a640-ffffffff8162a6b0: search_dev_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81666ef5)
Location: drivers/iommu/amd_iommu.c:219
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685595)
Location: drivers/iommu/amd_iommu.c:223
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bcad5)
Location: drivers/iommu/amd_iommu.c:212
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dfb45)
Location: drivers/iommu/amd_iommu.c:212
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8179787f)
Location: drivers/iommu/amd/iommu.c:192
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5fef)
Location: drivers/iommu/amd/iommu.c:201
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787bef)
Location: drivers/iommu/amd/iommu.c:157
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180f507)
Location: drivers/iommu/amd/iommu.c:157
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In drivers/iommu/amd/iommu.c (ffffffff81950107)
Location: drivers/iommu/amd/iommu.c:158
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In drivers/iommu/amd/iommu.c (ffffffff81ab5162)
Location: drivers/iommu/amd/iommu.c:202
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In drivers/iommu/amd/iommu.c (ffffffff81affd32)
Location: drivers/iommu/amd/iommu.c:202
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b53a42)
Location: drivers/iommu/amd/iommu.c:205
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a5595)
Location: drivers/iommu/amd_iommu.c:212
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682f85)
Location: drivers/iommu/amd_iommu.c:212
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3805)
Location: drivers/iommu/amd_iommu.c:212
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816edf05)
Location: drivers/iommu/amd_iommu.c:212
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>

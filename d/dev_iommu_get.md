# Function: <code>dev_iommu_get</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f108)
Location: drivers/iommu/iommu.c:170
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff817bb308)
Location: drivers/iommu/iommu.c:172
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff8179e738)
Location: drivers/iommu/iommu.c:179
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff818265d8)
Location: drivers/iommu/iommu.c:191
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81965d5d)
Location: drivers/iommu/iommu.c:193
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81acf4dd)
Location: drivers/iommu/iommu.c:258
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81b1e16d)
Location: drivers/iommu/iommu.c:290
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b742b9)
Location: drivers/iommu/iommu.c:333
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:iommu_init_device
Direct callers:
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81b741d0-ffffffff81b7425b: dev_iommu_get.part.0 (STB_LOCAL)
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

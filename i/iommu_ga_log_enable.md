# Function: <code>iommu_ga_log_enable</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4754)
Location: drivers/iommu/amd_iommu_init.c:695
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca4a9)
Location: drivers/iommu/amd_iommu_init.c:704
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630e89)
Location: drivers/iommu/amd_iommu_init.c:749
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166bd4d)
Location: drivers/iommu/amd_iommu_init.c:749
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd_iommu_init.c (ffffffff8168a5d2)
Location: drivers/iommu/amd_iommu_init.c:752
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd_iommu_init.c (ffffffff816c1f95)
Location: drivers/iommu/amd_iommu_init.c:740
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd_iommu_init.c (ffffffff816e4eb5)
Location: drivers/iommu/amd_iommu_init.c:741
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd/init.c (ffffffff8179b39c)
Location: drivers/iommu/amd/init.c:741
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
In drivers/iommu/amd/init.c (ffffffff817a9709)
Location: drivers/iommu/amd/init.c:791
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
In drivers/iommu/amd/init.c (ffffffff8178b373)
Location: drivers/iommu/amd/init.c:787
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff818127d0)
Location: drivers/iommu/amd/init.c:814
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff818127d0-ffffffff8181296b: iommu_ga_log_enable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81953750)
Location: drivers/iommu/amd/init.c:818
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81953750-ffffffff81953903: iommu_ga_log_enable.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff81ab9422)
Location: drivers/iommu/amd/init.c:901
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd/init.c (ffffffff81b0588f)
Location: drivers/iommu/amd/init.c:936
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd/init.c (ffffffff81b592cf)
Location: drivers/iommu/amd/init.c:951
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd_iommu_init.c (ffffffff816aa995)
Location: drivers/iommu/amd_iommu_init.c:741
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd_iommu_init.c (ffffffff816884d5)
Location: drivers/iommu/amd_iommu_init.c:741
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd_iommu_init.c (ffffffff816d8b75)
Location: drivers/iommu/amd_iommu_init.c:741
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
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
In drivers/iommu/amd_iommu_init.c (ffffffff816f3125)
Location: drivers/iommu/amd_iommu_init.c:741
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
</details>
</li>
</ul>

## Differences

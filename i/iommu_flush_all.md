# Function: <code>iommu_flush_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815323f3)
Location: drivers/iommu/amd_iommu.c:952
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/intel-iommu.c (ffffffff81538ca9)
Location: drivers/iommu/intel-iommu.c:3958
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81586bca)
Location: drivers/iommu/amd_iommu.c:1048
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158d759)
Location: drivers/iommu/intel-iommu.c:4055
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b418a)
Location: drivers/iommu/amd_iommu.c:1137
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/intel-iommu.c (ffffffff815ba9d9)
Location: drivers/iommu/intel-iommu.c:4146
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c9ff6)
Location: drivers/iommu/amd_iommu.c:1196
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d0688)
Location: drivers/iommu/intel-iommu.c:4141
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel-iommu.c (ffffffff81637468)
Location: drivers/iommu/intel-iommu.c:4047
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel-iommu.c (ffffffff816716a4)
Location: drivers/iommu/intel-iommu.c:4089
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel-iommu.c (ffffffff8168f974)
Location: drivers/iommu/intel-iommu.c:4098
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel-iommu.c (ffffffff816c81f8)
Location: drivers/iommu/intel-iommu.c:3938
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel-iommu.c (ffffffff816eb1a8)
Location: drivers/iommu/intel-iommu.c:4214
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff817a1a98)
Location: drivers/iommu/intel/iommu.c:4092
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff817af468)
Location: drivers/iommu/intel/iommu.c:3488
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff81791958)
Location: drivers/iommu/intel/iommu.c:3525
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff81819168)
Location: drivers/iommu/intel/iommu.c:3520
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff81959ce6)
Location: drivers/iommu/intel/iommu.c:3236
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff81ac0a96)
Location: drivers/iommu/intel/iommu.c:3116
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff81b0d306)
Location: drivers/iommu/intel/iommu.c:3003
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
In drivers/iommu/intel/iommu.c (ffffffff81b608d5)
Location: drivers/iommu/intel/iommu.c:2868
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_suspend
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e5d8)
Location: drivers/iommu/intel-iommu.c:4214
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel-iommu.c (ffffffff816dee68)
Location: drivers/iommu/intel-iommu.c:4214
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
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
In drivers/iommu/intel-iommu.c (ffffffff816f9478)
Location: drivers/iommu/intel-iommu.c:4214
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
```
</details>
</li>
</ul>

## Differences

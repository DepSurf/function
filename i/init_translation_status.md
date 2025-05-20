# Function: <code>init_translation_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81fab17a)
Location: drivers/iommu/intel-iommu.c:555
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81fd7cec)
Location: drivers/iommu/intel-iommu.c:562
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8201594c)
Location: drivers/iommu/intel-iommu.c:563
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff820f75fd)
Location: drivers/iommu/intel-iommu.c:564
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff826ff06b)
Location: drivers/iommu/amd_iommu_init.c:281
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700cde)
Location: drivers/iommu/intel-iommu.c:537
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff827295a7)
Location: drivers/iommu/amd_iommu_init.c:281
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272aa00)
Location: drivers/iommu/intel-iommu.c:539
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e1819)
Location: drivers/iommu/amd_iommu_init.c:284
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e32d8)
Location: drivers/iommu/intel-iommu.c:420
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828fc304)
Location: drivers/iommu/amd_iommu_init.c:269
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828fdc2d)
Location: drivers/iommu/intel-iommu.c:414
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff829052c2)
Location: drivers/iommu/amd_iommu_init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82906c95)
Location: drivers/iommu/intel-iommu.c:422
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1c0b3)
Location: drivers/iommu/amd/init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1db50)
Location: drivers/iommu/intel/iommu.c:426
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83009e9d)
Location: drivers/iommu/amd/init.c:276
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b867)
Location: drivers/iommu/intel/iommu.c:419
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832149ce)
Location: drivers/iommu/amd/init.c:272
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff83216210)
Location: drivers/iommu/intel/iommu.c:428
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832fdfba)
Location: drivers/iommu/amd/init.c:273
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff832ffa66)
Location: drivers/iommu/intel/iommu.c:410
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b6bc5)
Location: drivers/iommu/amd/init.c:275
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff834b880a)
Location: drivers/iommu/intel/iommu.c:343
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83ef1e0a)
Location: drivers/iommu/amd/init.c:246
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
```
In drivers/iommu/intel/iommu.c (ffffffff83ef551a)
Location: drivers/iommu/intel/iommu.c:318
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83717a3a)
Location: drivers/iommu/amd/init.c:249
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
```
In drivers/iommu/intel/iommu.c (ffffffff8371b09b)
Location: drivers/iommu/intel/iommu.c:318
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8394b4ba)
Location: drivers/iommu/amd/init.c:244
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
```
In drivers/iommu/intel/iommu.c (ffffffff8394eb7b)
Location: drivers/iommu/intel/iommu.c:181
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ecaa9)
Location: drivers/iommu/amd_iommu_init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828ee472)
Location: drivers/iommu/intel-iommu.c:422
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e3f36)
Location: drivers/iommu/amd_iommu_init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e5909)
Location: drivers/iommu/intel-iommu.c:422
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff829005e5)
Location: drivers/iommu/amd_iommu_init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82901fb8)
Location: drivers/iommu/intel-iommu.c:422
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82906324)
Location: drivers/iommu/amd_iommu_init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82907cf7)
Location: drivers/iommu/intel-iommu.c:422
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
</ul>

## Differences

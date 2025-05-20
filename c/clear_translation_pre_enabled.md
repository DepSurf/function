# Function: <code>clear_translation_pre_enabled</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81fab1ab)
Location: drivers/iommu/intel-iommu.c:550
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff81fd7d1b)
Location: drivers/iommu/intel-iommu.c:557
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff8201597b)
Location: drivers/iommu/intel-iommu.c:558
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff820f762e)
Location: drivers/iommu/intel-iommu.c:559
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff826ff2e1)
Location: drivers/iommu/amd_iommu_init.c:276
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700d0f)
Location: drivers/iommu/intel-iommu.c:532
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff827295d3)
Location: drivers/iommu/amd_iommu_init.c:276
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272aa30)
Location: drivers/iommu/intel-iommu.c:534
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e1846)
Location: drivers/iommu/amd_iommu_init.c:279
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e3308)
Location: drivers/iommu/intel-iommu.c:415
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff816c2598)
Location: drivers/iommu/amd_iommu_init.c:264
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828fdc5b)
Location: drivers/iommu/intel-iommu.c:409
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff816e54b8)
Location: drivers/iommu/amd_iommu_init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82906cc3)
Location: drivers/iommu/intel-iommu.c:417
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff8179b7fc)
Location: drivers/iommu/amd/init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1db81)
Location: drivers/iommu/intel/iommu.c:421
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff817a9c43)
Location: drivers/iommu/amd/init.c:271
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b898)
Location: drivers/iommu/intel/iommu.c:414
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff8178b976)
Location: drivers/iommu/amd/init.c:267
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff83216244)
Location: drivers/iommu/intel/iommu.c:423
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff81812e52)
Location: drivers/iommu/amd/init.c:268
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff832ffa9a)
Location: drivers/iommu/intel/iommu.c:405
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff81953dbc)
Location: drivers/iommu/amd/init.c:270
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/iommu.c (ffffffff834b8839)
Location: drivers/iommu/intel/iommu.c:338
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff81ab986a)
Location: drivers/iommu/amd/init.c:241
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
```
In drivers/iommu/intel/iommu.c (ffffffff83ef55ec)
Location: drivers/iommu/intel/iommu.c:313
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff81b05ce2)
Location: drivers/iommu/amd/init.c:244
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
```
In drivers/iommu/intel/iommu.c (ffffffff8371b144)
Location: drivers/iommu/intel/iommu.c:313
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd/init.c (ffffffff81b59a82)
Location: drivers/iommu/amd/init.c:239
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
```
In drivers/iommu/intel/iommu.c (ffffffff8394ec24)
Location: drivers/iommu/intel/iommu.c:176
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff816aaf98)
Location: drivers/iommu/amd_iommu_init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828ee4a0)
Location: drivers/iommu/intel-iommu.c:417
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff816888f8)
Location: drivers/iommu/amd_iommu_init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e5937)
Location: drivers/iommu/intel-iommu.c:417
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff816d9178)
Location: drivers/iommu/amd_iommu_init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82901fe6)
Location: drivers/iommu/intel-iommu.c:417
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/amd_iommu_init.c (ffffffff816f3728)
Location: drivers/iommu/amd_iommu_init.c:265
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82907d25)
Location: drivers/iommu/intel-iommu.c:417
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
</ul>

## Differences

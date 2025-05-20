# Function: <code>intel_disable_iommus</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff820f821a)
Location: drivers/iommu/intel-iommu.c:4728
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff827018c9)
Location: drivers/iommu/intel-iommu.c:4633
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff8272b5ea)
Location: drivers/iommu/intel-iommu.c:4675
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff828e3ee3)
Location: drivers/iommu/intel-iommu.c:4684
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff828fe387)
Location: drivers/iommu/intel-iommu.c:4479
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff829073c5)
Location: drivers/iommu/intel-iommu.c:4755
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void intel_disable_iommus();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a6690)
Location: drivers/iommu/intel/iommu.c:4634
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8179fb20-ffffffff8179fb55: intel_disable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void intel_disable_iommus();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b3070)
Location: drivers/iommu/intel/iommu.c:4031
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff817ad6c0-ffffffff817ad6f5: intel_disable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intel_disable_iommus();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81796080)
Location: drivers/iommu/intel/iommu.c:4117
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81790050-ffffffff81790085: intel_disable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void intel_disable_iommus();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181df4a)
Location: drivers/iommu/intel/iommu.c:4112
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff818178c0-ffffffff818178f5: intel_disable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void intel_disable_iommus();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195e3f2)
Location: drivers/iommu/intel/iommu.c:3857
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81958860-ffffffff8195889b: intel_disable_iommus (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff83ef5df3)
Location: drivers/iommu/intel/iommu.c:3733
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
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
In drivers/iommu/intel/iommu.c (ffffffff8371b8a3)
Location: drivers/iommu/intel/iommu.c:3620
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
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
In drivers/iommu/intel/iommu.c (ffffffff8394f3b3)
Location: drivers/iommu/intel/iommu.c:3469
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
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
In drivers/iommu/intel-iommu.c (ffffffff828eeba2)
Location: drivers/iommu/intel-iommu.c:4755
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff828e6039)
Location: drivers/iommu/intel-iommu.c:4755
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff829026e8)
Location: drivers/iommu/intel-iommu.c:4755
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff82908427)
Location: drivers/iommu/intel-iommu.c:4755
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>

# Function: <code>domain_update_iommu_snooping</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81536f89)
Location: drivers/iommu/intel-iommu.c:784
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
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
In drivers/iommu/intel-iommu.c (ffffffff8158e28d)
Location: drivers/iommu/intel-iommu.c:791
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff815bbd87)
Location: drivers/iommu/intel-iommu.c:792
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff815d19d8)
Location: drivers/iommu/intel-iommu.c:797
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff816387a8)
Location: drivers/iommu/intel-iommu.c:770
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff81673b74)
Location: drivers/iommu/intel-iommu.c:772
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff81692128)
Location: drivers/iommu/intel-iommu.c:648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff816ca0c3)
Location: drivers/iommu/intel-iommu.c:633
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff816ed093)
Location: drivers/iommu/intel-iommu.c:644
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel/iommu.c (ffffffff817a4e49)
Location: drivers/iommu/intel/iommu.c:652
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int domain_update_iommu_snooping(struct intel_iommu *skip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817acd20)
Location: drivers/iommu/intel/iommu.c:642
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
**Symbols:**

```
ffffffff817acd20-ffffffff817acd7f: domain_update_iommu_snooping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int domain_update_iommu_snooping(struct intel_iommu *skip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178fb00)
Location: drivers/iommu/intel/iommu.c:651
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
**Symbols:**

```
ffffffff8178fb00-ffffffff8178fb7e: domain_update_iommu_snooping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool domain_update_iommu_snooping(struct intel_iommu *skip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81817430)
Location: drivers/iommu/intel/iommu.c:640
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
**Symbols:**

```
ffffffff81817430-ffffffff818174ae: domain_update_iommu_snooping (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b2803)
Location: drivers/iommu/intel-iommu.c:644
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff816904c3)
Location: drivers/iommu/intel-iommu.c:644
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff816e0d53)
Location: drivers/iommu/intel-iommu.c:644
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int domain_update_iommu_snooping(struct intel_iommu *skip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f6720)
Location: drivers/iommu/intel-iommu.c:644
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
```
**Symbols:**

```
ffffffff816f6720-ffffffff816f6786: domain_update_iommu_snooping (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
</ul>

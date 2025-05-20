# Function: <code>parse_ioapics_under_ir</code>

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
In drivers/iommu/intel_irq_remapping.c (ffffffff81fac244)
Location: drivers/iommu/intel_irq_remapping.c:930
Inline: True
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81fd8dde)
Location: drivers/iommu/intel_irq_remapping.c:930
Inline: True
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
In drivers/iommu/intel_irq_remapping.c (ffffffff82016aad)
Location: drivers/iommu/intel_irq_remapping.c:930
Inline: True
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
In drivers/iommu/intel_irq_remapping.c (ffffffff820f87f2)
Location: drivers/iommu/intel_irq_remapping.c:937
Inline: True
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
In drivers/iommu/intel_irq_remapping.c (ffffffff82701ea0)
Location: drivers/iommu/intel_irq_remapping.c:938
Inline: True
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8272bbb7)
Location: drivers/iommu/intel_irq_remapping.c:938
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff828e44c1)
Location: drivers/iommu/intel_irq_remapping.c:940
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff828feabb)
Location: drivers/iommu/intel_irq_remapping.c:965
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff82907c5e)
Location: drivers/iommu/intel_irq_remapping.c:965
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_ioapics_under_ir();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff82d1e30f)
Location: drivers/iommu/intel/irq_remapping.c:979
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff82d1e30f-ffffffff82d1e393: parse_ioapics_under_ir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_ioapics_under_ir();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff8300bfe8)
Location: drivers/iommu/intel/irq_remapping.c:977
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8300bfe8-ffffffff8300c06c: parse_ioapics_under_ir (STB_LOCAL)
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
In drivers/iommu/intel/irq_remapping.c (ffffffff83216e6d)
Location: drivers/iommu/intel/irq_remapping.c:981
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel/irq_remapping.c (ffffffff833006f2)
Location: drivers/iommu/intel/irq_remapping.c:988
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel/irq_remapping.c (ffffffff834b93c7)
Location: drivers/iommu/intel/irq_remapping.c:988
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel/irq_remapping.c (ffffffff83ef6485)
Location: drivers/iommu/intel/irq_remapping.c:982
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel/irq_remapping.c (ffffffff8371bf35)
Location: drivers/iommu/intel/irq_remapping.c:975
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel/irq_remapping.c (ffffffff8394fa25)
Location: drivers/iommu/intel/irq_remapping.c:975
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff828ef42f)
Location: drivers/iommu/intel_irq_remapping.c:965
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff828e68d2)
Location: drivers/iommu/intel_irq_remapping.c:965
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff82902f81)
Location: drivers/iommu/intel_irq_remapping.c:965
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff82908cc0)
Location: drivers/iommu/intel_irq_remapping.c:965
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
</ul>

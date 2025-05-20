# Function: <code>free_context_table</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81537528)
Location: drivers/iommu/intel-iommu.c:965
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff8158c029)
Location: drivers/iommu/intel-iommu.c:972
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff815b9769)
Location: drivers/iommu/intel-iommu.c:986
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff815cf489)
Location: drivers/iommu/intel-iommu.c:991
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff81636219)
Location: drivers/iommu/intel-iommu.c:957
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff81672509)
Location: drivers/iommu/intel-iommu.c:959
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff8169144b)
Location: drivers/iommu/intel-iommu.c:835
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff816c9411)
Location: drivers/iommu/intel-iommu.c:841
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff816ec3e1)
Location: drivers/iommu/intel-iommu.c:852
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_context_table(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a1bb0)
Location: drivers/iommu/intel/iommu.c:866
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff817a1bb0-ffffffff817a1c6c: free_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_context_table(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af200)
Location: drivers/iommu/intel/iommu.c:956
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff817af200-ffffffff817af2bc: free_context_table (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff817924c8)
Location: drivers/iommu/intel/iommu.c:972
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81819d89)
Location: drivers/iommu/intel/iommu.c:978
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff8195a903)
Location: drivers/iommu/intel/iommu.c:825
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81ac3eae)
Location: drivers/iommu/intel/iommu.c:787
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
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
In drivers/iommu/intel/iommu.c (ffffffff81b1087a)
Location: drivers/iommu/intel/iommu.c:787
Inline: True
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
In drivers/iommu/intel/iommu.c (ffffffff81b6531a)
Location: drivers/iommu/intel/iommu.c:647
Inline: True
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
In drivers/iommu/intel-iommu.c (ffffffff816b1d11)
Location: drivers/iommu/intel-iommu.c:852
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff8168f811)
Location: drivers/iommu/intel-iommu.c:852
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff816e00a1)
Location: drivers/iommu/intel-iommu.c:852
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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
In drivers/iommu/intel-iommu.c (ffffffff816fa6b1)
Location: drivers/iommu/intel-iommu.c:852
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
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

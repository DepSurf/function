# Function: <code>domain_update_iommu_coherency</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81536f05)
Location: drivers/iommu/intel-iommu.c:754
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff8158b1f5)
Location: drivers/iommu/intel-iommu.c:761
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff815b8945)
Location: drivers/iommu/intel-iommu.c:762
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff815ceb85)
Location: drivers/iommu/intel-iommu.c:767
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff816358f5)
Location: drivers/iommu/intel-iommu.c:740
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff81670fa5)
Location: drivers/iommu/intel-iommu.c:742
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff8168eef5)
Location: drivers/iommu/intel-iommu.c:618
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff816c63d5)
Location: drivers/iommu/intel-iommu.c:603
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff816e9345)
Location: drivers/iommu/intel-iommu.c:614
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void domain_update_iommu_coherency(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179eef0)
Location: drivers/iommu/intel/iommu.c:622
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
**Symbols:**

```
ffffffff8179eef0-ffffffff8179efd7: domain_update_iommu_coherency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void domain_update_iommu_coherency(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817acc30)
Location: drivers/iommu/intel/iommu.c:612
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
**Symbols:**

```
ffffffff817acc30-ffffffff817acd1c: domain_update_iommu_coherency (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff81790875)
Location: drivers/iommu/intel/iommu.c:621
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel/iommu.c (ffffffff818181b5)
Location: drivers/iommu/intel/iommu.c:610
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel/iommu.c (ffffffff8195a4d5)
Location: drivers/iommu/intel/iommu.c:490
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel/iommu.c (ffffffff81ac1b6a)
Location: drivers/iommu/intel/iommu.c:464
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel/iommu.c (ffffffff81b0e7fa)
Location: drivers/iommu/intel/iommu.c:464
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel/iommu.c (ffffffff81b6626a)
Location: drivers/iommu/intel/iommu.c:326
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff816aee25)
Location: drivers/iommu/intel-iommu.c:614
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff8168c785)
Location: drivers/iommu/intel-iommu.c:614
Inline: True
Inline callers:
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
In drivers/iommu/intel-iommu.c (ffffffff816dd005)
Location: drivers/iommu/intel-iommu.c:614
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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
In drivers/iommu/intel-iommu.c (ffffffff816f7d35)
Location: drivers/iommu/intel-iommu.c:614
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_update_iommu_cap
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

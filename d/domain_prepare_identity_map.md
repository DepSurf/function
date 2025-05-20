# Function: <code>domain_prepare_identity_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int domain_prepare_identity_map(struct device *dev, struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81537d90)
Location: drivers/iommu/intel-iommu.c:2510
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
```
**Symbols:**

```
ffffffff81537d90-ffffffff81537f0a: domain_prepare_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int domain_prepare_identity_map(struct device *dev, struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158c880)
Location: drivers/iommu/intel-iommu.c:2554
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff8158c880-ffffffff8158c9fa: domain_prepare_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int domain_prepare_identity_map(struct device *dev, struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b9fc0)
Location: drivers/iommu/intel-iommu.c:2631
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815b9fc0-ffffffff815ba13a: domain_prepare_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int domain_prepare_identity_map(struct device *dev, struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cff80)
Location: drivers/iommu/intel-iommu.c:2639
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815cff80-ffffffff815d00d1: domain_prepare_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int domain_prepare_identity_map(struct device *dev, struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81636d20)
Location: drivers/iommu/intel-iommu.c:2663
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81636d20-ffffffff81636e6d: domain_prepare_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int domain_prepare_identity_map(struct device *dev, struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81675551)
Location: drivers/iommu/intel-iommu.c:2719
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81675551-ffffffff81675697: domain_prepare_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int domain_prepare_identity_map(struct device *dev, struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816939db)
Location: drivers/iommu/intel-iommu.c:2716
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff816939db-ffffffff81693b21: domain_prepare_identity_map (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816cc514)
Location: drivers/iommu/intel-iommu.c:2682
Inline: True
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
In drivers/iommu/intel-iommu.c (ffffffff816efd5f)
Location: drivers/iommu/intel-iommu.c:2693
Inline: True
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In drivers/iommu/intel-iommu.c (ffffffff816b5545)
Location: drivers/iommu/intel-iommu.c:2693
Inline: True
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
In drivers/iommu/intel-iommu.c (ffffffff8169318f)
Location: drivers/iommu/intel-iommu.c:2693
Inline: True
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
In drivers/iommu/intel-iommu.c (ffffffff816e3a1f)
Location: drivers/iommu/intel-iommu.c:2693
Inline: True
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
In drivers/iommu/intel-iommu.c (ffffffff816fe0cb)
Location: drivers/iommu/intel-iommu.c:2693
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>

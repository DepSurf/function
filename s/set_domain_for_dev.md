# Function: <code>set_domain_for_dev</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dmar_domain *set_domain_for_dev(struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bcca0)
Location: drivers/iommu/intel-iommu.c:2547
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815bcca0-ffffffff815bcd9a: set_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dmar_domain *set_domain_for_dev(struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d28e0)
Location: drivers/iommu/intel-iommu.c:2555
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815d28e0-ffffffff815d29c6: set_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dmar_domain *set_domain_for_dev(struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816395e0)
Location: drivers/iommu/intel-iommu.c:2579
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff816395e0-ffffffff816396c6: set_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dmar_domain *set_domain_for_dev(struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81674820)
Location: drivers/iommu/intel-iommu.c:2635
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81674820-ffffffff8167491a: set_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dmar_domain *set_domain_for_dev(struct device *dev, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692e50)
Location: drivers/iommu/intel-iommu.c:2632
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81692e50-ffffffff81692f4a: set_domain_for_dev (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816cae05)
Location: drivers/iommu/intel-iommu.c:2621
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
In drivers/iommu/intel-iommu.c (ffffffff816ee575)
Location: drivers/iommu/intel-iommu.c:2632
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
In drivers/iommu/intel-iommu.c (ffffffff816b3ce5)
Location: drivers/iommu/intel-iommu.c:2632
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
In drivers/iommu/intel-iommu.c (ffffffff816919a5)
Location: drivers/iommu/intel-iommu.c:2632
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
In drivers/iommu/intel-iommu.c (ffffffff816e2235)
Location: drivers/iommu/intel-iommu.c:2632
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
In drivers/iommu/intel-iommu.c (ffffffff816fc89f)
Location: drivers/iommu/intel-iommu.c:2632
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

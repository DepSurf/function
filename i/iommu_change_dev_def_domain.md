# Function: <code>iommu_change_dev_def_domain</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iommu_change_dev_def_domain(struct iommu_group *group, struct device *prev_dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:3078
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
**Symbols:**

```
ffffffff817bbc10-ffffffff817bbe8a: iommu_change_dev_def_domain (STB_LOCAL)
ffffffff81c0d625-ffffffff81c0d698: iommu_change_dev_def_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iommu_change_dev_def_domain(struct iommu_group *group, struct device *prev_dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:3057
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
**Symbols:**

```
ffffffff8179ed80-ffffffff8179effa: iommu_change_dev_def_domain (STB_LOCAL)
ffffffff81bff98c-ffffffff81bff9fc: iommu_change_dev_def_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iommu_change_dev_def_domain(struct iommu_group *group, struct device *prev_dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:3142
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
**Symbols:**

```
ffffffff81827d20-ffffffff81827feb: iommu_change_dev_def_domain (STB_LOCAL)
ffffffff81d01aa2-ffffffff81d01b12: iommu_change_dev_def_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iommu_change_dev_def_domain(struct iommu_group *group, struct device *prev_dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2874
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
**Symbols:**

```
ffffffff81967ca0-ffffffff81967f76: iommu_change_dev_def_domain (STB_LOCAL)
ffffffff81ec9f9f-ffffffff81ec9ff7: iommu_change_dev_def_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_change_dev_def_domain(struct iommu_group *group, struct device *prev_dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad1240)
Location: drivers/iommu/iommu.c:2831
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
**Symbols:**

```
ffffffff81ad1240-ffffffff81ad1524: iommu_change_dev_def_domain (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>

# Function: <code>__iommu_probe_device</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f0d0)
Location: drivers/iommu/iommu.c:193
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8178f0d0-ffffffff8178f33f: __iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bb2d0)
Location: drivers/iommu/iommu.c:195
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff817bb2d0-ffffffff817bb53f: __iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179e700)
Location: drivers/iommu/iommu.c:202
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8179e700-ffffffff8179e967: __iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818265a0)
Location: drivers/iommu/iommu.c:219
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff818265a0-ffffffff818267f5: __iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81966e30)
Location: drivers/iommu/iommu.c:221
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff81966e30-ffffffff81967068: __iommu_probe_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:304
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:probe_iommu_group
```
**Symbols:**

```
ffffffff81ad1a10-ffffffff81ad1d3e: __iommu_probe_device (STB_LOCAL)
ffffffff82097cf6-ffffffff82097d14: __iommu_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:336
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:probe_iommu_group
```
**Symbols:**

```
ffffffff81b1f4e0-ffffffff81b1f83b: __iommu_probe_device (STB_LOCAL)
ffffffff82118cab-ffffffff82118cc9: __iommu_probe_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __iommu_probe_device(struct device *dev, struct list_head *group_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:500
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:probe_iommu_group
```
**Symbols:**

```
ffffffff81b771f0-ffffffff81b77481: __iommu_probe_device (STB_LOCAL)
ffffffff821f6c5b-ffffffff821f6c70: __iommu_probe_device.cold (STB_LOCAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

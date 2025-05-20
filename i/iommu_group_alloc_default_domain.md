# Function: <code>iommu_group_alloc_default_domain</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1460
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8178e650-ffffffff8178e764: iommu_group_alloc_default_domain.isra.0 (STB_LOCAL)
ffffffff817906d9-ffffffff8179071b: iommu_group_alloc_default_domain.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type *bus, struct iommu_group *group, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1494
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff817ba920-ffffffff817baa47: iommu_group_alloc_default_domain (STB_LOCAL)
ffffffff81c0d5a5-ffffffff81c0d5e7: iommu_group_alloc_default_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type *bus, struct iommu_group *group, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1523
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8179e620-ffffffff8179e6f4: iommu_group_alloc_default_domain (STB_LOCAL)
ffffffff81bff94c-ffffffff81bff98c: iommu_group_alloc_default_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type *bus, struct iommu_group *group, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1538
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff81827c90-ffffffff81827d19: iommu_group_alloc_default_domain (STB_LOCAL)
ffffffff81d01a86-ffffffff81d01aa2: iommu_group_alloc_default_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type *bus, struct iommu_group *group, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1512
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff81967b20-ffffffff81967ba5: iommu_group_alloc_default_domain (STB_LOCAL)
ffffffff81ec9f83-ffffffff81ec9f9f: iommu_group_alloc_default_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type *bus, struct iommu_group *group, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81aceb10)
Location: drivers/iommu/iommu.c:1633
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff81aceb10-ffffffff81acebaa: iommu_group_alloc_default_domain (STB_LOCAL)
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
In drivers/iommu/iommu.c (ffffffff81b20268)
Location: drivers/iommu/iommu.c:1638
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_setup_default_domain
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
In drivers/iommu/iommu.c (ffffffff81b76c6d)
Location: drivers/iommu/iommu.c:1789
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_setup_default_domain
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

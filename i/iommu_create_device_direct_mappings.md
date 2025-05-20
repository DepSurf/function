# Function: <code>iommu_create_device_direct_mappings</code>

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
In drivers/iommu/iommu.c (ffffffff8178fb80)
Location: drivers/iommu/iommu.c:718
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8178fb80-ffffffff8178fd46: iommu_create_device_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bb9c0)
Location: drivers/iommu/iommu.c:727
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff817bb9c0-ffffffff817bbc0a: iommu_create_device_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179eb20)
Location: drivers/iommu/iommu.c:753
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8179eb20-ffffffff8179ed78: iommu_create_device_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:768
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff818278f0-ffffffff81827b8e: iommu_create_device_direct_mappings.isra.0 (STB_LOCAL)
ffffffff81d01a65-ffffffff81d01a86: iommu_create_device_direct_mappings.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:783
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff819672b0-ffffffff8196754f: iommu_create_device_direct_mappings.isra.0 (STB_LOCAL)
ffffffff81ec9f62-ffffffff81ec9f83: iommu_create_device_direct_mappings.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:914
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff81ad0ea0-ffffffff81ad1174: iommu_create_device_direct_mappings.isra.0 (STB_LOCAL)
ffffffff82097cd5-ffffffff82097cf6: iommu_create_device_direct_mappings.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iommu_create_device_direct_mappings(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:954
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
```
**Symbols:**

```
ffffffff81b1fee0-ffffffff81b20184: iommu_create_device_direct_mappings (STB_LOCAL)
ffffffff82118cee-ffffffff82118d0f: iommu_create_device_direct_mappings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iommu_create_device_direct_mappings(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1083
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff81b764c0-ffffffff81b76752: iommu_create_device_direct_mappings (STB_LOCAL)
ffffffff821f6c25-ffffffff821f6c46: iommu_create_device_direct_mappings.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

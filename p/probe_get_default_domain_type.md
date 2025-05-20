# Function: <code>probe_get_default_domain_type</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int probe_get_default_domain_type(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1635
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff8178d8c0-ffffffff8178d937: probe_get_default_domain_type (STB_LOCAL)
ffffffff8179051b-ffffffff8179057e: probe_get_default_domain_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int probe_get_default_domain_type(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1669
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff817ba800-ffffffff817ba891: probe_get_default_domain_type (STB_LOCAL)
ffffffff81c0d542-ffffffff81c0d5a5: probe_get_default_domain_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int probe_get_default_domain_type(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1690
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff8179e420-ffffffff8179e4b0: probe_get_default_domain_type (STB_LOCAL)
ffffffff81bff8ed-ffffffff81bff94c: probe_get_default_domain_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int probe_get_default_domain_type(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff81827490-ffffffff81827520: probe_get_default_domain_type (STB_LOCAL)
ffffffff81d01a06-ffffffff81d01a65: probe_get_default_domain_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int probe_get_default_domain_type(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1642
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff81967170-ffffffff81967224: probe_get_default_domain_type (STB_LOCAL)
ffffffff81ec9f05-ffffffff81ec9f62: probe_get_default_domain_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int probe_get_default_domain_type(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad0cf0)
Location: drivers/iommu/iommu.c:1756
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
**Symbols:**

```
ffffffff81ad0cf0-ffffffff81ad0df7: probe_get_default_domain_type (STB_LOCAL)
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
</ul>

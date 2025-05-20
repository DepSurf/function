# Function: <code>__iommu_attach_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81529ee0)
Location: drivers/iommu/iommu.c:1091
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81529ee0-ffffffff81529f58: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157d3d0)
Location: drivers/iommu/iommu.c:1081
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8157d3d0-ffffffff8157d457: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815a9940)
Location: drivers/iommu/iommu.c:1232
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff815a9940-ffffffff815a99c7: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bf580)
Location: drivers/iommu/iommu.c:1282
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff815bf580-ffffffff815bf606: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626120)
Location: drivers/iommu/iommu.c:1283
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81626120-ffffffff816261cd: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81660830)
Location: drivers/iommu/iommu.c:1284
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81660830-ffffffff816608e4: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167ece0)
Location: drivers/iommu/iommu.c:1351
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8167ece0-ffffffff8167ed94: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b69d0)
Location: drivers/iommu/iommu.c:1568
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816b69d0-ffffffff816b6a89: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d96d0)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816d96d0-ffffffff816d9789: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81790063)
Location: drivers/iommu/iommu.c:1911
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
Direct callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8178ea20-ffffffff8178eab1: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bac50)
Location: drivers/iommu/iommu.c:1941
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff817bac50-ffffffff817baccc: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f643)
Location: drivers/iommu/iommu.c:1962
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_deferred_attach
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff8179d0f0-ffffffff8179d16c: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81828633)
Location: drivers/iommu/iommu.c:1983
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_deferred_attach
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff81825e50-ffffffff81825ec9: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81966240)
Location: drivers/iommu/iommu.c:1961
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:__iommu_group_set_domain
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_deferred_attach
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_probe_device
```
**Symbols:**

```
ffffffff81966240-ffffffff819662dc: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acf790)
Location: drivers/iommu/iommu.c:1988
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:__iommu_group_set_domain
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_deferred_attach
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81acf790-ffffffff81acf838: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1e210)
Location: drivers/iommu/iommu.c:1973
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:iommu_deferred_attach
```
**Symbols:**

```
ffffffff81b1e210-ffffffff81b1e2b8: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b74a70)
Location: drivers/iommu/iommu.c:2240
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:__iommu_release_dma_ownership
  - drivers/iommu/iommu.c:__iommu_release_dma_ownership
  - drivers/iommu/iommu.c:iommu_detach_group
  - drivers/iommu/iommu.c:iommu_detach_group
  - drivers/iommu/iommu.c:iommu_deferred_attach
```
**Symbols:**

```
ffffffff81b74a70-ffffffff81b74b18: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c59b0)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffff8000108c59b0-ffff8000108c5abc: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc274)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
c09bc274-c09bc368: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096aed0)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
c00000000096aed0-c00000000096b028: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f120)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8169f120-ffffffff8169f1d9: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167cb10)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8167cb10-ffffffff8167cbc9: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cd390)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816cd390-ffffffff816cd449: __iommu_attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __iommu_attach_device(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7870)
Location: drivers/iommu/iommu.c:1624
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_attach_group
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816e7870-ffffffff816e7945: __iommu_attach_device (STB_LOCAL)
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

# Function: <code>iommu_group_add_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152b3f0)
Location: drivers/iommu/iommu.c:382
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff8152b3f0-ffffffff8152b793: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157e3f0)
Location: drivers/iommu/iommu.c:373
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff8157e3f0-ffffffff8157e7de: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aa990)
Location: drivers/iommu/iommu.c:511
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff815aa990-ffffffff815aad99: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c0570)
Location: drivers/iommu/iommu.c:544
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff815c0570-ffffffff815c099e: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626c40)
Location: drivers/iommu/iommu.c:546
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff81626c40-ffffffff816270a0: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:547
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff81662cfa-ffffffff81662d36: iommu_group_add_device.cold.22 (STB_LOCAL)
ffffffff81661940-ffffffff81661d50: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:613
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff816812dc-ffffffff81681318: iommu_group_add_device.cold.24 (STB_LOCAL)
ffffffff81680000-ffffffff81680410: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b76b0)
Location: drivers/iommu/iommu.c:631
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff816b76b0-ffffffff816b7928: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816da260)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff816da260-ffffffff816da4e5: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178ee30)
Location: drivers/iommu/iommu.c:790
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff8178ee30-ffffffff8178f0c8: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bb040)
Location: drivers/iommu/iommu.c:811
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff817bb040-ffffffff817bb2cc: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179d5c0)
Location: drivers/iommu/iommu.c:837
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff8179d5c0-ffffffff8179d84c: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81826310)
Location: drivers/iommu/iommu.c:852
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff81826310-ffffffff8182659c: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819665a0)
Location: drivers/iommu/iommu.c:865
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/vfio/vfio.c:vfio_noiommu_group_alloc
```
**Symbols:**

```
ffffffff819665a0-ffffffff81966831: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad1750)
Location: drivers/iommu/iommu.c:986
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff81ad1750-ffffffff81ad19f7: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1d710)
Location: drivers/iommu/iommu.c:1025
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff81b1d710-ffffffff81b1d8fc: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b74660)
Location: drivers/iommu/iommu.c:1213
Inline: False
```
**Symbols:**

```
ffffffff81b74660-ffffffff81b746d1: iommu_group_add_device (STB_GLOBAL)
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
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c6490)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffff8000108c6490-ffff8000108c6730: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bccf0)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_add_device
```
**Symbols:**

```
c09bccf0-c09bcf80: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096caa0)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_add_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
c00000000096caa0-c00000000096ce2c: iommu_group_add_device (STB_GLOBAL)
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
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169fcb0)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff8169fcb0-ffffffff8169ff35: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167d6a0)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff8167d6a0-ffffffff8167d925: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cdf20)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff816cdf20-ffffffff816ce1a5: iommu_group_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_group_add_device(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8460)
Location: drivers/iommu/iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff816e8460-ffffffff816e86fa: iommu_group_add_device (STB_GLOBAL)
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

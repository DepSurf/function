# Function: <code>pm_runtime_get_if_in_use</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81555de0)
Location: drivers/base/power/runtime.c:978
Inline: False
```
**Symbols:**

```
ffffffff81555de0-ffffffff81555e70: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a7e30)
Location: drivers/base/power/runtime.c:978
Inline: False
```
**Symbols:**

```
ffffffff815a7e30-ffffffff815a7ec0: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d6600)
Location: drivers/base/power/runtime.c:1056
Inline: False
```
**Symbols:**

```
ffffffff815d6600-ffffffff815d6690: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815eb010)
Location: drivers/base/power/runtime.c:1056
Inline: False
```
**Symbols:**

```
ffffffff815eb010-ffffffff815eb09b: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816523c0)
Location: drivers/base/power/runtime.c:1057
Inline: False
```
**Symbols:**

```
ffffffff816523c0-ffffffff8165244b: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168dca0)
Location: drivers/base/power/runtime.c:1057
Inline: False
```
**Symbols:**

```
ffffffff8168dca0-ffffffff8168dd2d: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816adef0)
Location: drivers/base/power/runtime.c:1064
Inline: False
```
**Symbols:**

```
ffffffff816adef0-ffffffff816adf7d: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e7e20)
Location: drivers/base/power/runtime.c:1093
Inline: False
```
**Symbols:**

```
ffffffff816e7e20-ffffffff816e7e92: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170be80)
Location: drivers/base/power/runtime.c:1095
Inline: False
```
**Symbols:**

```
ffffffff8170be80-ffffffff8170bef2: pm_runtime_get_if_in_use (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fb0e0)
Location: drivers/base/power/runtime.c:1095
Inline: False
Direct callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
**Symbols:**

```
ffff8000108fb0e0-ffff8000108fb1ec: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e6640)
Location: drivers/base/power/runtime.c:1095
Inline: False
Direct callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
**Symbols:**

```
c09e6640-c09e66dc: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000997640)
Location: drivers/base/power/runtime.c:1095
Inline: False
```
**Symbols:**

```
c000000000997640-c000000000997708: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058a18c)
Location: drivers/base/power/runtime.c:1095
Inline: False
```
**Symbols:**

```
ffffffe00058a18c-ffffffe00058a208: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d15d0)
Location: drivers/base/power/runtime.c:1095
Inline: False
```
**Symbols:**

```
ffffffff816d15d0-ffffffff816d1642: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ac8f0)
Location: drivers/base/power/runtime.c:1095
Inline: False
```
**Symbols:**

```
ffffffff816ac8f0-ffffffff816ac962: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ffb40)
Location: drivers/base/power/runtime.c:1095
Inline: False
```
**Symbols:**

```
ffffffff816ffb40-ffffffff816ffbb2: pm_runtime_get_if_in_use (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm_runtime_get_if_in_use(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171a470)
Location: drivers/base/power/runtime.c:1095
Inline: False
```
**Symbols:**

```
ffffffff8171a470-ffffffff8171a4e2: pm_runtime_get_if_in_use (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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

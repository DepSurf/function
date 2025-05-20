# Function: <code>pm_runtime_force_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557d30)
Location: drivers/base/power/runtime.c:1443
Inline: False
```
**Symbols:**

```
ffffffff81557d30-ffffffff81557da3: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9de0)
Location: drivers/base/power/runtime.c:1461
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
```
**Symbols:**

```
ffffffff815a9de0-ffffffff815a9e58: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d84d0)
Location: drivers/base/power/runtime.c:1637
Inline: True
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
```
**Symbols:**

```
ffffffff815d84d0-ffffffff815d8560: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ed0c0)
Location: drivers/base/power/runtime.c:1637
Inline: True
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff815ed0c0-ffffffff815ed148: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654470)
Location: drivers/base/power/runtime.c:1628
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff81654470-ffffffff816544fb: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168fab0)
Location: drivers/base/power/runtime.c:1642
Inline: True
```
**Symbols:**

```
ffffffff8168fab0-ffffffff8168fb9d: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816afe40)
Location: drivers/base/power/runtime.c:1650
Inline: True
```
**Symbols:**

```
ffffffff816afe40-ffffffff816aff2d: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9d40)
Location: drivers/base/power/runtime.c:1735
Inline: True
```
**Symbols:**

```
ffffffff816e9d40-ffffffff816e9e11: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170dda0)
Location: drivers/base/power/runtime.c:1740
Inline: True
```
**Symbols:**

```
ffffffff8170dda0-ffffffff8170de71: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c96b0)
Location: drivers/base/power/runtime.c:1765
Inline: False
```
**Symbols:**

```
ffffffff817c96b0-ffffffff817c97b6: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817de1b0)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
ffffffff817de1b0-ffffffff817de2b6: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c25b0)
Location: drivers/base/power/runtime.c:1787
Inline: False
```
**Symbols:**

```
ffffffff817c25b0-ffffffff817c26be: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184c360)
Location: drivers/base/power/runtime.c:1821
Inline: False
```
**Symbols:**

```
ffffffff8184c360-ffffffff8184c46e: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81991d20)
Location: drivers/base/power/runtime.c:1854
Inline: False
```
**Symbols:**

```
ffffffff81991d20-ffffffff81991e17: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b021c0)
Location: drivers/base/power/runtime.c:1868
Inline: False
```
**Symbols:**

```
ffffffff81b021c0-ffffffff81b022e2: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b502b0)
Location: drivers/base/power/runtime.c:1872
Inline: False
```
**Symbols:**

```
ffffffff81b502b0-ffffffff81b503d2: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba8830)
Location: drivers/base/power/runtime.c:1873
Inline: False
```
**Symbols:**

```
ffffffff81ba8830-ffffffff81ba8952: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd5c0)
Location: drivers/base/power/runtime.c:1740
Inline: True
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_suspend
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_suspend_noirq
```
**Symbols:**

```
ffff8000108fd5c0-ffff8000108fd6a0: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e8928)
Location: drivers/base/power/runtime.c:1740
Inline: True
Direct callers:
  - drivers/bus/ti-sysc.c:sysc_noirq_suspend
  - drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_suspend
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_suspend
```
**Symbols:**

```
c09e8928-c09e89f0: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999ef0)
Location: drivers/base/power/runtime.c:1740
Inline: True
```
**Symbols:**

```
c000000000999ef0-c00000000099a01c: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c2be)
Location: drivers/base/power/runtime.c:1740
Inline: True
```
**Symbols:**

```
ffffffe00058c2be-ffffffe00058c382: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d34f0)
Location: drivers/base/power/runtime.c:1740
Inline: True
```
**Symbols:**

```
ffffffff816d34f0-ffffffff816d35c1: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae7b0)
Location: drivers/base/power/runtime.c:1740
Inline: True
```
**Symbols:**

```
ffffffff816ae7b0-ffffffff816ae881: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701a60)
Location: drivers/base/power/runtime.c:1740
Inline: True
```
**Symbols:**

```
ffffffff81701a60-ffffffff81701b31: pm_runtime_force_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pm_runtime_force_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c6c0)
Location: drivers/base/power/runtime.c:1740
Inline: True
```
**Symbols:**

```
ffffffff8171c6c0-ffffffff8171c791: pm_runtime_force_suspend (STB_GLOBAL)
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

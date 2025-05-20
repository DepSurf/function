# Function: <code>clk_bulk_disable</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81543c2c)
Location: drivers/clk/clk-bulk.c:120
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff81543b80-ffffffff81543bc3: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815a6ddc)
Location: drivers/clk/clk-bulk.c:121
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff815a6d30-ffffffff815a6d73: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815de999)
Location: drivers/clk/clk-bulk.c:122
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff815de7a0-ffffffff815de7e2: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815f82c7)
Location: drivers/clk/clk-bulk.c:191
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff815f8060-ffffffff815f80a2: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8162a33f)
Location: drivers/clk/clk-bulk.c:208
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff8162a1c0-ffffffff8162a202: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8164bdff)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff8164bc80-ffffffff8164bcc2: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816fac50)
Location: drivers/clk/clk-bulk.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff816fac50-ffffffff816fac92: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81717600)
Location: drivers/clk/clk-bulk.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff81717600-ffffffff81717642: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816f88f0)
Location: drivers/clk/clk-bulk.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff816f88f0-ffffffff816f8932: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff817730b0)
Location: drivers/clk/clk-bulk.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff817730b0-ffffffff817730f2: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff818a8930)
Location: drivers/clk/clk-bulk.c:211
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff818a8930-ffffffff818a8986: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff819f3406)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff819f3340-ffffffff819f3396: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a3ba96)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff81a3b9d0-ffffffff81a3ba26: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a87356)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff81a87290-ffffffff81a872e6: clk_bulk_disable (STB_GLOBAL)
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
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffff8000107ba840)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
**Symbols:**

```
ffff8000107ba758-ffff8000107ba7b0: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (c08e6900)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
**Symbols:**

```
c08e6858-c08e6894: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffe00050996c)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffe0005098a0-ffffffe000509900: clk_bulk_disable (STB_GLOBAL)
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
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81611e5f)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff81611ce0-ffffffff81611d22: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816063af)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff81606230-ffffffff81606272: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8163fc3f)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff8163fac0-ffffffff8163fb02: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_disable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81659f8f)
Location: drivers/clk/clk-bulk.c:211
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_enable
```
**Symbols:**

```
ffffffff81659e10-ffffffff81659e52: clk_bulk_disable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

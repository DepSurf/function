# Function: <code>clk_bulk_unprepare</code>

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
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81543ccc)
Location: drivers/clk/clk-bulk.c:71
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81543b30-ffffffff81543b73: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815a6cec)
Location: drivers/clk/clk-bulk.c:71
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff815a6c40-ffffffff815a6c83: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815de95e)
Location: drivers/clk/clk-bulk.c:72
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff815de6f0-ffffffff815de732: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815f828c)
Location: drivers/clk/clk-bulk.c:141
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff815f7fb0-ffffffff815f7ff2: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8162a305)
Location: drivers/clk/clk-bulk.c:158
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff8162a110-ffffffff8162a152: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8164bdc5)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff8164bbd0-ffffffff8164bc12: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816faba0)
Location: drivers/clk/clk-bulk.c:161
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff816faba0-ffffffff816fabe2: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81717550)
Location: drivers/clk/clk-bulk.c:161
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81717550-ffffffff81717592: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816f8840)
Location: drivers/clk/clk-bulk.c:161
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff816f8840-ffffffff816f8882: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81773000)
Location: drivers/clk/clk-bulk.c:161
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81773000-ffffffff81773042: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff818a8870)
Location: drivers/clk/clk-bulk.c:161
Inline: False
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff818a8870-ffffffff818a88c6: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff819f34d6)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff819f32d0-ffffffff819f3326: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a3bb66)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81a3b960-ffffffff81a3b9b6: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a87426)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81a87220-ffffffff81a87276: clk_bulk_unprepare (STB_GLOBAL)
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
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffff8000107ba738)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
**Symbols:**

```
ffff8000107ba650-ffff8000107ba6a8: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (c08e6844)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
**Symbols:**

```
c08e679c-c08e67d8: clk_bulk_unprepare (STB_GLOBAL)
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
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffe00050987e)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffe0005097b2-ffffffe000509812: clk_bulk_unprepare (STB_GLOBAL)
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
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81611e25)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81611c30-ffffffff81611c72: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81606375)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81606180-ffffffff816061c2: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8163fc05)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff8163fa10-ffffffff8163fa52: clk_bulk_unprepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_bulk_unprepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81659f55)
Location: drivers/clk/clk-bulk.c:161
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
```
**Symbols:**

```
ffffffff81659d60-ffffffff81659da2: clk_bulk_unprepare (STB_GLOBAL)
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

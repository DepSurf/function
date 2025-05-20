# Function: <code>clk_bulk_enable</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81543bd0)
Location: drivers/clk/clk-bulk.c:136
Inline: False
```
**Symbols:**

```
ffffffff81543bd0-ffffffff81543c6d: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815a6d80)
Location: drivers/clk/clk-bulk.c:137
Inline: False
```
**Symbols:**

```
ffffffff815a6d80-ffffffff815a6e1d: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:138
Inline: False
```
**Symbols:**

```
ffffffff815de984-ffffffff815de9bf: clk_bulk_enable.cold.2 (STB_LOCAL)
ffffffff815de7f0-ffffffff815de843: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:207
Inline: False
```
**Symbols:**

```
ffffffff815f82b2-ffffffff815f82ed: clk_bulk_enable.cold.7 (STB_LOCAL)
ffffffff815f80b0-ffffffff815f8103: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:224
Inline: False
```
**Symbols:**

```
ffffffff8162a32b-ffffffff8162a365: clk_bulk_enable.cold (STB_LOCAL)
ffffffff8162a210-ffffffff8162a262: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff8164bdeb-ffffffff8164be25: clk_bulk_enable.cold (STB_LOCAL)
ffffffff8164bcd0-ffffffff8164bd22: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff816faeb6-ffffffff816faed7: clk_bulk_enable.cold (STB_LOCAL)
ffffffff816faca0-ffffffff816facf3: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81c0408c-ffffffff81c040ad: clk_bulk_enable.cold (STB_LOCAL)
ffffffff81717650-ffffffff817176a3: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81bf5a26-ffffffff81bf5a47: clk_bulk_enable.cold (STB_LOCAL)
ffffffff816f8940-ffffffff816f8993: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81cf2fab-ffffffff81cf2fcc: clk_bulk_enable.cold (STB_LOCAL)
ffffffff81773100-ffffffff81773153: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81ebb13b-ffffffff81ebb15c: clk_bulk_enable.cold (STB_LOCAL)
ffffffff818a8990-ffffffff818a89eb: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff819f33b0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff819f33b0-ffffffff819f346c: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a3ba40)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81a3ba40-ffffffff81a3bafc: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a87300)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81a87300-ffffffff81a873bc: clk_bulk_enable (STB_GLOBAL)
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
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffff8000107ba7b0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/iommu/arm-smmu.c:arm_smmu_runtime_resume
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
**Symbols:**

```
ffff8000107ba7b0-ffff8000107ba85c: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (c08e6894)
Location: drivers/clk/clk-bulk.c:227
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
**Symbols:**

```
c08e6894-c08e6914: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffe000509900)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffe000509900-ffffffe00050998e: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81611e4b-ffffffff81611e85: clk_bulk_enable.cold (STB_LOCAL)
ffffffff81611d30-ffffffff81611d82: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff8160639b-ffffffff816063d5: clk_bulk_enable.cold (STB_LOCAL)
ffffffff81606280-ffffffff816062d2: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff8163fc2b-ffffffff8163fc65: clk_bulk_enable.cold (STB_LOCAL)
ffffffff8163fb10-ffffffff8163fb62: clk_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int clk_bulk_enable(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:227
Inline: False
```
**Symbols:**

```
ffffffff81659f7b-ffffffff81659fb5: clk_bulk_enable.cold (STB_LOCAL)
ffffffff81659e60-ffffffff81659eb2: clk_bulk_enable (STB_GLOBAL)
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

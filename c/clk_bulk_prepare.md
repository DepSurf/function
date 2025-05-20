# Function: <code>clk_bulk_prepare</code>

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
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81543c70)
Location: drivers/clk/clk-bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81543c70-ffffffff81543d0d: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815a6c90)
Location: drivers/clk/clk-bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff815a6c90-ffffffff815a6d2d: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:87
Inline: False
```
**Symbols:**

```
ffffffff815de949-ffffffff815de984: clk_bulk_prepare.cold.1 (STB_LOCAL)
ffffffff815de740-ffffffff815de793: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:156
Inline: False
```
**Symbols:**

```
ffffffff815f8277-ffffffff815f82b2: clk_bulk_prepare.cold.6 (STB_LOCAL)
ffffffff815f8000-ffffffff815f8053: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:173
Inline: False
```
**Symbols:**

```
ffffffff8162a2f1-ffffffff8162a32b: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff8162a160-ffffffff8162a1b2: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff8164bdb1-ffffffff8164bdeb: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff8164bc20-ffffffff8164bc72: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff816fae95-ffffffff816faeb6: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff816fabf0-ffffffff816fac43: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81c0406b-ffffffff81c0408c: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff817175a0-ffffffff817175f3: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81bf5a05-ffffffff81bf5a26: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff816f8890-ffffffff816f88e3: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81cf2f8a-ffffffff81cf2fab: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff81773050-ffffffff817730a3: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81ebb11a-ffffffff81ebb13b: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff818a88d0-ffffffff818a892b: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff819f3480)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff819f3480-ffffffff819f353c: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a3bb10)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81a3bb10-ffffffff81a3bbcc: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a873d0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81a873d0-ffffffff81a8748c: clk_bulk_prepare (STB_GLOBAL)
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
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffff8000107ba6a8)
Location: drivers/clk/clk-bulk.c:176
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
**Symbols:**

```
ffff8000107ba6a8-ffff8000107ba754: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (c08e67d8)
Location: drivers/clk/clk-bulk.c:176
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
**Symbols:**

```
c08e67d8-c08e6858: clk_bulk_prepare (STB_GLOBAL)
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
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffe000509812)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffe000509812-ffffffe0005098a0: clk_bulk_prepare (STB_GLOBAL)
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
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81611e11-ffffffff81611e4b: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff81611c80-ffffffff81611cd2: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81606361-ffffffff8160639b: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff816061d0-ffffffff81606222: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff8163fbf1-ffffffff8163fc2b: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff8163fa60-ffffffff8163fab2: clk_bulk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int clk_bulk_prepare(int num_clks, const struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-bulk.c (0)
Location: drivers/clk/clk-bulk.c:176
Inline: False
```
**Symbols:**

```
ffffffff81659f41-ffffffff81659f7b: clk_bulk_prepare.cold (STB_LOCAL)
ffffffff81659db0-ffffffff81659e02: clk_bulk_prepare (STB_GLOBAL)
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

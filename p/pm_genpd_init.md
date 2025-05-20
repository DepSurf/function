# Function: <code>pm_genpd_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815af570)
Location: drivers/base/power/domain.c:1264
Inline: False
```
**Symbols:**

```
ffffffff815af570-ffffffff815af7f6: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815df090)
Location: drivers/base/power/domain.c:1440
Inline: False
```
**Symbols:**

```
ffffffff815df090-ffffffff815df2dc: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f3db0)
Location: drivers/base/power/domain.c:1522
Inline: False
```
**Symbols:**

```
ffffffff815f3db0-ffffffff815f4017: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165bbf0)
Location: drivers/base/power/domain.c:1645
Inline: False
```
**Symbols:**

```
ffffffff8165bbf0-ffffffff8165be67: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81697920)
Location: drivers/base/power/domain.c:1643
Inline: False
```
**Symbols:**

```
ffffffff81697920-ffffffff81697bc2: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1722
Inline: False
```
**Symbols:**

```
ffffffff816b9426-ffffffff816b943e: pm_genpd_init.cold.22 (STB_LOCAL)
ffffffff816b6e00-ffffffff816b70b7: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1781
Inline: False
```
**Symbols:**

```
ffffffff816f34e7-ffffffff816f34ff: pm_genpd_init.cold (STB_LOCAL)
ffffffff816f0c90-ffffffff816f0f8e: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1776
Inline: False
```
**Symbols:**

```
ffffffff81717932-ffffffff8171794a: pm_genpd_init.cold (STB_LOCAL)
ffffffff81715130-ffffffff8171542e: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1765
Inline: False
```
**Symbols:**

```
ffffffff817d3502-ffffffff817d351a: pm_genpd_init.cold (STB_LOCAL)
ffffffff817d1c80-ffffffff817d1f8e: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1925
Inline: False
```
**Symbols:**

```
ffffffff81c0efe9-ffffffff81c0f002: pm_genpd_init.cold (STB_LOCAL)
ffffffff817e61e0-ffffffff817e6536: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1921
Inline: False
```
**Symbols:**

```
ffffffff81c01153-ffffffff81c0116c: pm_genpd_init.cold (STB_LOCAL)
ffffffff817ca5e0-ffffffff817ca934: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1961
Inline: False
```
**Symbols:**

```
ffffffff81d03f94-ffffffff81d03fad: pm_genpd_init.cold (STB_LOCAL)
ffffffff818546b0-ffffffff81854a04: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:2044
Inline: False
```
**Symbols:**

```
ffffffff81ecc884-ffffffff81ecc8a2: pm_genpd_init.cold (STB_LOCAL)
ffffffff8199ad50-ffffffff8199b103: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0beb0)
Location: drivers/base/power/domain.c:2024
Inline: False
```
**Symbols:**

```
ffffffff81b0beb0-ffffffff81b0c28a: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b59ef0)
Location: drivers/base/power/domain.c:2050
Inline: False
```
**Symbols:**

```
ffffffff81b59ef0-ffffffff81b5a2ca: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa18b0)
Location: drivers/pmdomain/core.c:2057
Inline: False
```
**Symbols:**

```
ffffffff81aa18b0-ffffffff81aa1cf6: pm_genpd_init (STB_GLOBAL)
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
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010907d28)
Location: drivers/base/power/domain.c:1776
Inline: False
Direct callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/qcom/rpmhpd.c:rpmhpd_probe
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
```
**Symbols:**

```
ffff800010907d28-ffff800010907fac: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f22d8)
Location: drivers/base/power/domain.c:1776
Inline: False
Direct callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_add_clk_domain
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/dove/pmu.c:dove_init_pmu
  - drivers/soc/dove/pmu.c:dove_init_pmu_legacy
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/imx/gpc.c:imx_pgc_power_domain_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_add_pm_domains
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
```
**Symbols:**

```
c09f22d8-c09f2574: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a7820)
Location: drivers/base/power/domain.c:1776
Inline: False
```
**Symbols:**

```
c0000000009a7820-c0000000009a7b48: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058d8ee)
Location: drivers/base/power/domain.c:1776
Inline: False
```
**Symbols:**

```
ffffffe00058d8ee-ffffffe00058db3a: pm_genpd_init (STB_GLOBAL)
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
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1776
Inline: False
```
**Symbols:**

```
ffffffff816ddc62-ffffffff816ddc7a: pm_genpd_init.cold (STB_LOCAL)
ffffffff816db460-ffffffff816db75e: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1776
Inline: False
```
**Symbols:**

```
ffffffff816b82c6-ffffffff816b82de: pm_genpd_init.cold (STB_LOCAL)
ffffffff816b5ae0-ffffffff816b5dde: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1776
Inline: False
```
**Symbols:**

```
ffffffff8170b5f2-ffffffff8170b60a: pm_genpd_init.cold (STB_LOCAL)
ffffffff81708df0-ffffffff817090ee: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pm_genpd_init(struct generic_pm_domain *genpd, struct dev_power_governor *gov, bool is_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:1776
Inline: False
```
**Symbols:**

```
ffffffff81725fdf-ffffffff81725ff7: pm_genpd_init.cold (STB_LOCAL)
ffffffff81723960-ffffffff81723c5e: pm_genpd_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

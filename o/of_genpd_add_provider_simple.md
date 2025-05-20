# Function: <code>of_genpd_add_provider_simple</code>

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
int of_genpd_add_provider_simple(struct device_node *np, struct generic_pm_domain *genpd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010907838)
Location: drivers/base/power/domain.c:2028
Inline: False
Direct callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
**Symbols:**

```
ffff800010907838-ffff800010907948: of_genpd_add_provider_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_genpd_add_provider_simple(struct device_node *np, struct generic_pm_domain *genpd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f1c00)
Location: drivers/base/power/domain.c:2028
Inline: False
Direct callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_add_clk_domain
  - drivers/soc/dove/pmu.c:dove_init_pmu
  - drivers/soc/imx/gpc.c:imx_pgc_power_domain_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_add_pm_domains
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
```
**Symbols:**

```
c09f1c00-c09f1d20: of_genpd_add_provider_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_genpd_add_provider_simple(struct device_node *np, struct generic_pm_domain *genpd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a98d0)
Location: drivers/base/power/domain.c:2028
Inline: False
```
**Symbols:**

```
c0000000009a98d0-c0000000009a9a44: of_genpd_add_provider_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_genpd_add_provider_simple(struct device_node *np, struct generic_pm_domain *genpd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058edcc)
Location: drivers/base/power/domain.c:2028
Inline: False
```
**Symbols:**

```
ffffffe00058edcc-ffffffe00058eed6: of_genpd_add_provider_simple (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>

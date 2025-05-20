# Function: <code>of_genpd_add_provider_onecell</code>

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
int of_genpd_add_provider_onecell(struct device_node *np, struct genpd_onecell_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010907948)
Location: drivers/base/power/domain.c:2085
Inline: False
Direct callers:
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/qcom/rpmhpd.c:rpmhpd_probe
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
```
**Symbols:**

```
ffff800010907948-ffff800010907b34: of_genpd_add_provider_onecell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_genpd_add_provider_onecell(struct device_node *np, struct genpd_onecell_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f1d20)
Location: drivers/base/power/domain.c:2085
Inline: False
Direct callers:
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
```
**Symbols:**

```
c09f1d20-c09f1f18: of_genpd_add_provider_onecell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_genpd_add_provider_onecell(struct device_node *np, struct genpd_onecell_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a9a50)
Location: drivers/base/power/domain.c:2085
Inline: False
```
**Symbols:**

```
c0000000009a9a50-c0000000009a9d14: of_genpd_add_provider_onecell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_genpd_add_provider_onecell(struct device_node *np, struct genpd_onecell_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058f164)
Location: drivers/base/power/domain.c:2085
Inline: False
```
**Symbols:**

```
ffffffe00058f164-ffffffe00058f342: of_genpd_add_provider_onecell (STB_GLOBAL)
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

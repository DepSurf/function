# Function: <code>soc_device_register</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct soc_device *soc_device_register(struct soc_device_attribute *soc_dev_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/soc.c (ffffffff81b78617)
Location: drivers/base/soc.c:128
Inline: True
Direct callers:
  - drivers/base/soc.c:soc_bus_register
```
**Symbols:**

```
ffffffff8211a9bf-ffffffff8211a9d3: soc_device_register.cold (STB_LOCAL)
ffffffff81b785c0-ffffffff81b78719: soc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct soc_device *soc_device_register(struct soc_device_attribute *soc_dev_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/soc.c (ffffffff83951c34)
Location: drivers/base/soc.c:128
Inline: True
Inline callers:
  - drivers/base/soc.c:soc_bus_register
Direct callers:
  - drivers/base/soc.c:soc_bus_register
```
**Symbols:**

```
ffffffff81bcc3c0-ffffffff81bcc561: soc_device_register.part.0 (STB_LOCAL)
ffffffff821f8844-ffffffff821f8859: soc_device_register.cold (STB_LOCAL)
ffffffff81bcc580-ffffffff81bcc5e5: soc_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct soc_device *soc_device_register(struct soc_device_attribute *soc_dev_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/soc.c (ffff800011497eec)
Location: drivers/base/soc.c:121
Inline: True
Inline callers:
  - drivers/base/soc.c:soc_bus_register
Direct callers:
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_init
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/base/soc.c:soc_bus_register
```
**Symbols:**

```
ffff80001091e8c0-ffff80001091e9c8: soc_device_register.part.0 (STB_LOCAL)
ffff80001091e9c8-ffff80001091ea24: soc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct soc_device *soc_device_register(struct soc_device_attribute *soc_dev_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/soc.c (c1598c0c)
Location: drivers/base/soc.c:121
Inline: True
Inline callers:
  - drivers/base/soc.c:soc_bus_register
Direct callers:
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_device
  - arch/arm/mach-imx/cpu.c:imx_soc_device_init
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/samsung/exynos-chipid.c:exynos_chipid_early_init
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_soc_device_register
  - drivers/base/soc.c:soc_bus_register
```
**Symbols:**

```
c0a03c20-c0a03d00: soc_device_register.part.0 (STB_LOCAL)
c0a03d00-c0a03d58: soc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct soc_device *soc_device_register(struct soc_device_attribute *soc_dev_attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/soc.c (c0000000013aba88)
Location: drivers/base/soc.c:121
Inline: True
Inline callers:
  - drivers/base/soc.c:soc_bus_register
Direct callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/base/soc.c:soc_bus_register
```
**Symbols:**

```
c0000000009c3b00-c0000000009c3c80: soc_device_register.part.0 (STB_LOCAL)
c0000000009c3c80-c0000000009c3cd8: soc_device_register (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>

# Function: <code>hisi_clk_init</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct hisi_clock_data *hisi_clk_init(struct device_node *np, int nr_clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clk.c (ffff8000107d00f0)
Location: drivers/clk/hisilicon/clk.c:58
Inline: True
Direct callers:
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_early_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_sctrl_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pctrl_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pmuctrl_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_iomcu_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media2_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media1_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_sctrl_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pmuctrl_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pctrl_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_acpu_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_ao_init
```
**Symbols:**

```
ffff8000107d00f0-ffff8000107d01d0: hisi_clk_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct hisi_clock_data *hisi_clk_init(struct device_node *np, int nr_clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/hisilicon/clk.c (c08f7b40)
Location: drivers/clk/hisilicon/clk.c:58
Inline: True
Direct callers:
  - drivers/clk/hisilicon/clk-hi3620.c:hi3620_clk_init
  - drivers/clk/hisilicon/clk-hip04.c:hip04_clk_init
  - drivers/clk/hisilicon/clk-hix5hd2.c:hix5hd2_clk_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_early_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_sctrl_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pctrl_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pmuctrl_init
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_iomcu_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media2_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media1_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_sctrl_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pmuctrl_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pctrl_init
  - drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_acpu_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_ao_init
```
**Symbols:**

```
c08f7b40-c08f7c00: hisi_clk_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
<b>Arch</b>
<ul>
</ul>

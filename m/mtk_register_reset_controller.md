# Function: <code>mtk_register_reset_controller</code>

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
void mtk_register_reset_controller(struct device_node *np, unsigned int num_regs, int regofs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/reset.c (ffff8000107e3330)
Location: drivers/clk/mediatek/reset.c:127
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_peri_probe
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_infra_probe
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init
```
**Symbols:**

```
ffff8000107e3330-ffff8000107e337c: mtk_register_reset_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mtk_register_reset_controller(struct device_node *np, unsigned int num_regs, int regofs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/reset.c (c090045c)
Location: drivers/clk/mediatek/reset.c:127
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init
  - drivers/clk/mediatek/clk-mt7629-eth.c:clk_mt7629_ethsys_init
  - drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_pciesys_init
  - drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_ssusbsys_init
  - drivers/clk/mediatek/clk-mt8135.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt8135.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init
```
**Symbols:**

```
c090045c-c0900480: mtk_register_reset_controller (STB_GLOBAL)
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

# Function: <code>reset_controller_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff814df370)
Location: drivers/reset/core.c:62
Inline: False
```
**Symbols:**

```
ffffffff814df370-ffffffff814df3d4: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815302a0)
Location: drivers/reset/core.c:67
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff815302a0-ffffffff81530310: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155c870)
Location: drivers/reset/core.c:71
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff8155c870-ffffffff8155c8e0: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815712d0)
Location: drivers/reset/core.c:72
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff815712d0-ffffffff8157133e: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d55a0)
Location: drivers/reset/core.c:85
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff815d55a0-ffffffff815d560e: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e370)
Location: drivers/reset/core.c:88
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff8160e370-ffffffff8160e3e0: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162ae90)
Location: drivers/reset/core.c:88
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff8162ae90-ffffffff8162af00: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8165ea60)
Location: drivers/reset/core.c:97
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff8165ea60-ffffffff8165ead0: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681150)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81681150-ffffffff816811c0: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732d6c)
Location: drivers/reset/core.c:98
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81732320-ffffffff81732393: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174ef2c)
Location: drivers/reset/core.c:99
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff8174e3d0-ffffffff8174e443: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732e3c)
Location: drivers/reset/core.c:99
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81731f50-ffffffff81731fc3: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b3753)
Location: drivers/reset/core.c:99
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff817b26b0-ffffffff817b2723: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818ef257)
Location: drivers/reset/core.c:100
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff818ee050-ffffffff818ee0cb: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a46f37)
Location: drivers/reset/core.c:100
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81a45bd0-ffffffff81a45c4b: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a910d7)
Location: drivers/reset/core.c:100
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81a8fd80-ffffffff81a8fdfb: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae3787)
Location: drivers/reset/core.c:100
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81ae27c0-ffffffff81ae283b: reset_controller_register (STB_GLOBAL)
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
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084bfb8)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_init
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller_common
  - drivers/clk/rockchip/softrst.c:rockchip_register_softrst
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
  - drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
```
**Symbols:**

```
ffff80001084bfb8-ffff80001084c03c: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c095835c)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - arch/arm/mach-imx/src.c:imx_src_init
  - drivers/clk/hisilicon/reset.c:hisi_reset_init
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller_common
  - drivers/clk/meson/meson8b.c:meson8b_clkc_init_common
  - drivers/clk/rockchip/softrst.c:rockchip_register_softrst
  - drivers/clk/tegra/clk.c:tegra_add_of_provider
  - drivers/soc/dove/pmu.c:pmu_reset_init
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
**Symbols:**

```
c095835c-c09583d0: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ea4e0)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
c0000000008ea4e0-c0000000008ea598: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052b8b0)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffe00052b8b0-ffffffe00052b928: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646bd0)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81646bd0-ffffffff81646c40: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627030)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81627030-ffffffff816270a0: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81674f90)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff81674f90-ffffffff81675000: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reset_controller_register(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168f5f0)
Location: drivers/reset/core.c:96
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_register
```
**Symbols:**

```
ffffffff8168f5f0-ffffffff8168f660: reset_controller_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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

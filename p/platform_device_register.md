# Function: <code>platform_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154e6f0)
Location: drivers/base/platform.c:439
Inline: False
Direct callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff8154e6f0-ffffffff8154e719: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815a04e0)
Location: drivers/base/platform.c:459
Inline: False
Direct callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff815a04e0-ffffffff815a0509: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ceb20)
Location: drivers/base/platform.c:473
Inline: False
Direct callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff815ceb20-ffffffff815ceb49: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e3580)
Location: drivers/base/platform.c:473
Inline: False
Direct callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff815e3580-ffffffff815e35a9: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8164a730)
Location: drivers/base/platform.c:473
Inline: False
Direct callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff8164a730-ffffffff8164a759: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81685ca0)
Location: drivers/base/platform.c:472
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffff81685ca0-ffffffff81685cc9: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a5940)
Location: drivers/base/platform.c:472
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
**Symbols:**

```
ffffffff816a5940-ffffffff816a5969: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816de910)
Location: drivers/base/platform.c:512
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff816de910-ffffffff816de93b: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817020b0)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff817020b0-ffffffff8170211f: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc509)
Location: drivers/base/platform.c:651
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff817bbc30-ffffffff817bbcb3: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1139)
Location: drivers/base/platform.c:803
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff817d0880-ffffffff817d0903: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4b57)
Location: drivers/base/platform.c:802
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff817b42a0-ffffffff817b4323: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e127)
Location: drivers/base/platform.c:766
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff8183dbd0-ffffffff8183dc53: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81980f22)
Location: drivers/base/platform.c:775
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff819808a0-ffffffff81980926: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aeead2)
Location: drivers/base/platform.c:775
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81aee3c0-ffffffff81aee446: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3cec2)
Location: drivers/base/platform.c:775
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81b3c780-ffffffff81b3c806: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94a02)
Location: drivers/base/platform.c:775
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_add_devices
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - arch/x86/kernel/sev.c:snp_init_platform_device
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
**Symbols:**

```
ffffffff81b942c0-ffffffff81b94346: platform_device_register (STB_GLOBAL)
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
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ed608)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/rtc/rtc-efi-platform.c:rtc_init
```
**Symbols:**

```
ffff8000108ed608-ffff8000108ed678: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09db4d8)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-highbank/highbank.c:highbank_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-omap2/devices.c:omap_init_vout
  - arch/arm/mach-omap2/fb.c:omap_init_fb
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_pandora_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_logicpd_torpedo_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_logicpd_torpedo_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_igep0020_rev_f_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_igep0020_rev_f_legacy_init
  - arch/arm/mach-tegra/board-paz00.c:tegra_paz00_wifikill_init
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/mfd/sm501.c:sm501_register_device
  - drivers/rtc/rtc-efi-platform.c:rtc_init
```
**Symbols:**

```
c09db4d8-c09db544: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000985780)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - arch/powerpc/kernel/legacy_serial.c:serial_dev_init
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
c000000000985780-c000000000985820: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe00058078e)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
```
**Symbols:**

```
ffffffe00058078e-ffffffe0005807fc: platform_device_register (STB_GLOBAL)
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
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c7800)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff816c7800-ffffffff816c786f: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a2b00)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff816a2b00-ffffffff816a2b6f: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f5d70)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff816f5d70-ffffffff816f5ddf: platform_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int platform_device_register(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710600)
Location: drivers/base/platform.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:add_rtc_cmos
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
  - drivers/base/platform.c:platform_add_devices
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81710600-ffffffff8171066f: platform_device_register (STB_GLOBAL)
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

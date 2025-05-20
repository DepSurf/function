# Function: <code>gpiod_set_raw_value_cansleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426470)
Location: drivers/gpio/gpiolib.c:1708
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
```
**Symbols:**

```
ffffffff81426470-ffffffff81426490: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146fbe0)
Location: drivers/gpio/gpiolib.c:2716
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
```
**Symbols:**

```
ffffffff8146fbe0-ffffffff8146fc61: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491f50)
Location: drivers/gpio/gpiolib.c:2925
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
```
**Symbols:**

```
ffffffff81491f50-ffffffff81491fd1: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149bb80)
Location: drivers/gpio/gpiolib.c:2932
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
```
**Symbols:**

```
ffffffff8149bb80-ffffffff8149bbff: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9fc0)
Location: drivers/gpio/gpiolib.c:3250
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
```
**Symbols:**

```
ffffffff814d9fc0-ffffffff814da03f: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508950)
Location: drivers/gpio/gpiolib.c:3441
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
```
**Symbols:**

```
ffffffff81508950-ffffffff81508988: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d460)
Location: drivers/gpio/gpiolib.c:3689
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
```
**Symbols:**

```
ffffffff8151d460-ffffffff8151d498: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154b500)
Location: drivers/gpio/gpiolib.c:3778
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8154b500-ffffffff8154b536: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c730)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8156c730-ffffffff8156c766: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4545
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8161489e-ffffffff816148f3: gpiod_set_raw_value_cansleep.cold (STB_LOCAL)
ffffffff81610810-ffffffff81610863: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81bf60a8-ffffffff81bf60fd: gpiod_set_raw_value_cansleep.cold (STB_LOCAL)
ffffffff81636ba0-ffffffff81636bf3: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3346
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81be7f4e-ffffffff81be7fa3: gpiod_set_raw_value_cansleep.cold (STB_LOCAL)
ffffffff8161a4c0-ffffffff8161a513: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3405
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81ce1a70-ffffffff81ce1ac5: gpiod_set_raw_value_cansleep.cold (STB_LOCAL)
ffffffff81689860-ffffffff816898b3: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a682e)
Location: drivers/gpio/gpiolib.c:3526
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff81ea833d-ffffffff81ea8391: gpiod_set_raw_value_cansleep.cold (STB_LOCAL)
ffffffff817a67f0-ffffffff817a685d: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818be760)
Location: drivers/gpio/gpiolib.c:3596
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff818be760-ffffffff818be804: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901900)
Location: drivers/gpio/gpiolib.c:3637
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff81901900-ffffffff819019b9: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949510)
Location: drivers/gpio/gpiolib.c:3830
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff81949510-ffffffff819495a8: gpiod_set_raw_value_cansleep (STB_GLOBAL)
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
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bfb40)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
**Symbols:**

```
ffff8000106bfb40-ffff8000106bfb94: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860280)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
**Symbols:**

```
c0860280-c08602c4: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083d9f0)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
c00000000083d9f0-c00000000083da78: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6fbe)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffe0004a6fbe-ffffffe0004a7008: gpiod_set_raw_value_cansleep (STB_GLOBAL)
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
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561ef0)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81561ef0-ffffffff81561f26: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552d40)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81552d40-ffffffff81552d76: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560a60)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81560a60-ffffffff81560a96: gpiod_set_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_set_raw_value_cansleep(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157a900)
Location: drivers/gpio/gpiolib.c:4132
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8157a900-ffffffff8157a936: gpiod_set_raw_value_cansleep (STB_GLOBAL)
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

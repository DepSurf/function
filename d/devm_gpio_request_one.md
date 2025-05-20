# Function: <code>devm_gpio_request_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81423d80)
Location: drivers/gpio/devres.c:353
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81423d80-ffffffff81423e0e: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8146d390)
Location: drivers/gpio/devres.c:353
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff8146d390-ffffffff8146d420: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8148f260)
Location: drivers/gpio/devres.c:353
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff8148f260-ffffffff8148f2f0: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81498d40)
Location: drivers/gpio/devres.c:363
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff81498d40-ffffffff81498dd0: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff814d7030)
Location: drivers/gpio/devres.c:366
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff814d7030-ffffffff814d70c0: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff815061f0)
Location: drivers/gpio/devres.c:408
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff815061f0-ffffffff81506280: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81521530)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81521530-ffffffff815215c0: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8154fa10)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8154fa10-ffffffff8154fa9f: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81570f00)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81570f00-ffffffff81570f8f: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81615310)
Location: drivers/gpio/gpiolib-devres.c:441
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81615310-ffffffff8161539f: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81639610)
Location: drivers/gpio/gpiolib-devres.c:439
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81639610-ffffffff8163969f: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8161d260)
Location: drivers/gpio/gpiolib-devres.c:439
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8161d260-ffffffff8161d2ef: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c810)
Location: drivers/gpio/gpiolib-devres.c:439
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8168c810-ffffffff8168c8a6: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff817a9e00)
Location: drivers/gpio/gpiolib-devres.c:439
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff817a9e00-ffffffff817a9eb5: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff818c2920)
Location: drivers/gpio/gpiolib-devres.c:425
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff818c2920-ffffffff818c29d5: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81905820)
Location: drivers/gpio/gpiolib-devres.c:370
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81905820-ffffffff819058d5: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8194d230)
Location: drivers/gpio/gpiolib-devres.c:370
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8194d230-ffffffff8194d2e5: devm_gpio_request_one (STB_GLOBAL)
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
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffff8000106c7088)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
**Symbols:**

```
ffff8000106c7088-ffff8000106c713c: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c0864a34)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
**Symbols:**

```
c0864a34-c0864ac0: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c000000000843cc0)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
c000000000843cc0-c000000000843dbc: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aab10)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffe0004aab10-ffffffe0004aab98: devm_gpio_request_one (STB_GLOBAL)
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
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff815666c0)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff815666c0-ffffffff8156674f: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81557510)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81557510-ffffffff8155759f: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81565230)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81565230-ffffffff815652bf: devm_gpio_request_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devm_gpio_request_one(struct device *dev, unsigned int gpio, long unsigned int flags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8157f150)
Location: drivers/gpio/gpiolib-devres.c:456
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8157f150-ffffffff8157f1df: devm_gpio_request_one (STB_GLOBAL)
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

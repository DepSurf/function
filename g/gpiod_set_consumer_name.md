# Function: <code>gpiod_set_consumer_name</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151b1c0)
Location: drivers/gpio/gpiolib.c:3373
Inline: False
```
**Symbols:**

```
ffffffff8151b1c0-ffffffff8151b219: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81549220)
Location: drivers/gpio/gpiolib.c:3462
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81549220-ffffffff81549277: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a640)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8156a640-ffffffff8156a697: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4222
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff816149a4-ffffffff81614a01: gpiod_set_consumer_name.cold (STB_LOCAL)
ffffffff81610920-ffffffff81610996: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3046
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81bf620d-ffffffff81bf626a: gpiod_set_consumer_name.cold (STB_LOCAL)
ffffffff81636d10-ffffffff81636d86: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3023
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81be80b3-ffffffff81be8110: gpiod_set_consumer_name.cold (STB_LOCAL)
ffffffff8161a630-ffffffff8161a6a6: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3072
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81ce1c58-ffffffff81ce1cb5: gpiod_set_consumer_name.cold (STB_LOCAL)
ffffffff81689a30-ffffffff81689aa6: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3193
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81ea84c5-ffffffff81ea8522: gpiod_set_consumer_name.cold (STB_LOCAL)
ffffffff817a69a0-ffffffff817a6a2c: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818beb20)
Location: drivers/gpio/gpiolib.c:3263
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff818beb20-ffffffff818bebec: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901cb0)
Location: drivers/gpio/gpiolib.c:3304
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81901cb0-ffffffff81901d78: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819497f0)
Location: drivers/gpio/gpiolib.c:3497
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff819497f0-ffffffff819498b8: gpiod_set_consumer_name (STB_GLOBAL)
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
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bdd50)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffff8000106bdd50-ffff8000106bddc4: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085da24)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
c085da24-c085da8c: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a3c0)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
c00000000083a3c0-c00000000083a454: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4c28)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffe0004a4c28-ffffffe0004a4c90: gpiod_set_consumer_name (STB_GLOBAL)
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
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155fe00)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8155fe00-ffffffff8155fe57: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550c50)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81550c50-ffffffff81550ca7: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e970)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8155e970-ffffffff8155e9c7: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc *desc, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578800)
Location: drivers/gpio/gpiolib.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81578800-ffffffff81578857: gpiod_set_consumer_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>dev_pm_domain_detach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81554990)
Location: drivers/base/power/common.c:125
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_shutdown
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81554990-ffffffff815549ba: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815a6990)
Location: drivers/base/power/common.c:127
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815a6990-ffffffff815a69ba: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815d5150)
Location: drivers/base/power/common.c:127
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815d5150-ffffffff815d517a: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815e9c10)
Location: drivers/base/power/common.c:127
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815e9c10-ffffffff815e9c3b: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81650fb0)
Location: drivers/base/power/common.c:127
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81650fb0-ffffffff81650fde: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8168c860)
Location: drivers/base/power/common.c:168
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8168c860-ffffffff8168c88d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816acab0)
Location: drivers/base/power/common.c:185
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816acab0-ffffffff816acadd: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816e6560)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/soundwire/bus_type.c:sdw_drv_remove
  - drivers/soundwire/bus_type.c:sdw_drv_probe
```
**Symbols:**

```
ffffffff816e6560-ffffffff816e658d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8170a930)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8170a930-ffffffff8170a95d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817c5910)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/opp/core.c:_opp_detach_genpd
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817c5910-ffffffff817c593d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817da420)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_remove
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_remove
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817da420-ffffffff817da44d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817be7e0)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_remove
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_remove
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817be7e0-ffffffff817be80d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81848b60)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_remove
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_remove
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81848b60-ffffffff81848b8d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8198da10)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_remove
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_remove
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8198da10-ffffffff8198da51: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81afd8f0)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_remove
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_remove
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81afd8f0-ffffffff81afd931: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81b4bce0)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_remove
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_remove
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81b4bce0-ffffffff81b4bd21: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81ba40d0)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_remove
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_remove
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81ba40d0-ffffffff81ba4111: dev_pm_domain_detach (STB_GLOBAL)
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
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffff8000108f9140)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
  - drivers/amba/bus.c:amba_probe
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffff8000108f9140-ffff8000108f9184: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c09e4a04)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/opp/core.c:_opp_detach_genpd
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c09e4a04-c09e4a38: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c0000000009952a0)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/opp/core.c:_opp_detach_genpd
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c0000000009952a0-c0000000009952f4: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffe000588c1e)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/opp/core.c:_opp_detach_genpd
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffe000588c1e-ffffffe000588c54: dev_pm_domain_detach (STB_GLOBAL)
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
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816d0080)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816d0080-ffffffff816d00ad: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816ab3b0)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
```
**Symbols:**

```
ffffffff816ab3b0-ffffffff816ab3dd: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816fe5f0)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816fe5f0-ffffffff816fe61d: dev_pm_domain_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_domain_detach(struct device *dev, bool power_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81718e40)
Location: drivers/base/power/common.c:183
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_remove
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_remove
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81718e40-ffffffff81718e6d: dev_pm_domain_detach (STB_GLOBAL)
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

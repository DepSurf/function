# Function: <code>dev_pm_domain_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815549c0)
Location: drivers/base/power/common.c:101
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815549c0-ffffffff815549de: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815a69c0)
Location: drivers/base/power/common.c:103
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815a69c0-ffffffff815a69de: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815d5180)
Location: drivers/base/power/common.c:103
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815d5180-ffffffff815d519e: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff815e9c40)
Location: drivers/base/power/common.c:103
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815e9c40-ffffffff815e9c5f: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81650fe0)
Location: drivers/base/power/common.c:103
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81650fe0-ffffffff81650fff: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8168c8e0)
Location: drivers/base/power/common.c:104
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8168c8e0-ffffffff8168c90e: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816acbd0)
Location: drivers/base/power/common.c:104
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816acbd0-ffffffff816acbfe: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816e6680)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/soundwire/bus_type.c:sdw_drv_probe
```
**Symbols:**

```
ffffffff816e6680-ffffffff816e66b5: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8170aa50)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8170aa50-ffffffff8170aa85: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817c59c0)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817c59c0-ffffffff817c59f9: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817da4d0)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817da4d0-ffffffff817da509: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff817be890)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817be890-ffffffff817be8b8: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81848c10)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81848c10-ffffffff81848c38: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff8198db70)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8198db70-ffffffff8198dbac: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81afda90)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81afda90-ffffffff81afdacc: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81b4be80)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81b4be80-ffffffff81b4bebc: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81ba42c0)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_probe
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/spi/spi.c:spi_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81ba42c0-ffffffff81ba42fc: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffff8000108f9290)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_probe
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffff8000108f9290-ffff8000108f92f4: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c09e4c24)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_probe
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c09e4c24-c09e4c58: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (c000000000995450)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c000000000995450-c0000000009954b4: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffe000588dfc)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffe000588dfc-ffffffe000588e44: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816d01a0)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816d01a0-ffffffff816d01d5: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816ab4d0)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
```
**Symbols:**

```
ffffffff816ab4d0-ffffffff816ab505: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff816fe710)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816fe710-ffffffff816fe745: dev_pm_domain_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dev_pm_domain_attach(struct device *dev, bool power_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/common.c (ffffffff81718fc0)
Location: drivers/base/power/common.c:102
Inline: True
Direct callers:
  - drivers/tty/serdev/core.c:serdev_drv_probe
  - drivers/base/platform.c:platform_drv_probe
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81718fc0-ffffffff81718ff5: dev_pm_domain_attach (STB_GLOBAL)
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

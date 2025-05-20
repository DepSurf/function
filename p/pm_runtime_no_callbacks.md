# Function: <code>pm_runtime_no_callbacks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815560e0)
Location: drivers/base/power/runtime.c:1274
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815560e0-ffffffff81556129: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a8120)
Location: drivers/base/power/runtime.c:1278
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815a8120-ffffffff815a8169: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d68f0)
Location: drivers/base/power/runtime.c:1366
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815d68f0-ffffffff815d6939: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815eb2f0)
Location: drivers/base/power/runtime.c:1366
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815eb2f0-ffffffff815eb339: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816526d0)
Location: drivers/base/power/runtime.c:1358
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816526d0-ffffffff81652719: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168dfb0)
Location: drivers/base/power/runtime.c:1358
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8168dfb0-ffffffff8168dffe: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae1c0)
Location: drivers/base/power/runtime.c:1365
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816ae1c0-ffffffff816ae20e: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e81b0)
Location: drivers/base/power/runtime.c:1449
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816e81b0-ffffffff816e8205: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170c210)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8170c210-ffffffff8170c265: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c75f0)
Location: drivers/base/power/runtime.c:1474
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817c75f0-ffffffff817c7645: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dc060)
Location: drivers/base/power/runtime.c:1506
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817dc060-ffffffff817dc0b5: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c0420)
Location: drivers/base/power/runtime.c:1506
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817c0420-ffffffff817c0475: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184a790)
Location: drivers/base/power/runtime.c:1542
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8184a790-ffffffff8184a7e5: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8198f6d0)
Location: drivers/base/power/runtime.c:1581
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8198f6d0-ffffffff8198f721: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81aff820)
Location: drivers/base/power/runtime.c:1594
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81aff820-ffffffff81aff871: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4dbd0)
Location: drivers/base/power/runtime.c:1594
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81b4dbd0-ffffffff81b4dc21: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba6150)
Location: drivers/base/power/runtime.c:1595
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81ba6150-ffffffff81ba61a1: pm_runtime_no_callbacks (STB_GLOBAL)
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
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fb028)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffff8000108fb028-ffff8000108fb0e0: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e646c)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c09e646c-c09e64cc: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000997ce0)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c000000000997ce0-c000000000997da0: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058a5aa)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffe00058a5aa-ffffffe00058a644: pm_runtime_no_callbacks (STB_GLOBAL)
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
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d1960)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
```
**Symbols:**

```
ffffffff816d1960-ffffffff816d19b5: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816acc80)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
```
**Symbols:**

```
ffffffff816acc80-ffffffff816acccf: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ffed0)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816ffed0-ffffffff816fff25: pm_runtime_no_callbacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_runtime_no_callbacks(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171a7a0)
Location: drivers/base/power/runtime.c:1451
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8171a7a0-ffffffff8171a7ec: pm_runtime_no_callbacks (STB_GLOBAL)
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

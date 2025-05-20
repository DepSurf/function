# Function: <code>bus_find_device_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81549b70)
Location: drivers/base/bus.c:372
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:store_drivers_probe
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_attach
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81549b70-ffffffff81549b87: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159c0b6)
Location: drivers/base/bus.c:371
Inline: True
Inline callers:
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_attach
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff8159b7c0-ffffffff8159b7d7: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815ca616)
Location: drivers/base/bus.c:371
Inline: True
Inline callers:
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_attach
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff815c9d20-ffffffff815c9d37: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815df2d6)
Location: drivers/base/bus.c:371
Inline: True
Inline callers:
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_attach
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff815dea60-ffffffff815dea77: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81646306)
Location: drivers/base/bus.c:371
Inline: True
Inline callers:
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_attach
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff81645a90-ffffffff81645aa7: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816817e5)
Location: drivers/base/bus.c:369
Inline: True
Inline callers:
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
Direct callers:
  - drivers/base/devcon.c:generic_match
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_attach
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff81680ef0-ffffffff81680f07: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a1285)
Location: drivers/base/bus.c:372
Inline: True
Inline callers:
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
Direct callers:
  - drivers/base/devcon.c:generic_match
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_attach
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff816a0980-ffffffff816a0997: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *bus_find_device_by_name(struct bus_type *bus, struct device *start, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816da055)
Location: drivers/base/bus.c:362
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/net/phy/phy_device.c:phy_connect
```
**Symbols:**

```
ffffffff816d98c0-ffffffff816d98d7: bus_find_device_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fe005)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffffffff8170781c)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff817446b8)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (ffffffff817bc615)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (ffffffff8190325c)
Location: include/linux/device.h:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b7405)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffffffff817c25c1)
Location: include/linux/device/bus.h:172
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81885895)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cc135)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/net/phy/phy_device.c (ffffffff8189415c)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817afaa5)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/net/phy/phy_device.c (ffffffff81875eec)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81838dd5)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/net/phy/phy_device.c (ffffffff81906a6c)
Location: include/linux/device/bus.h:172
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197b325)
Location: include/linux/device/bus.h:176
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5991a)
Location: include/linux/device/bus.h:176
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8191d205)
Location: include/linux/device/bus.h:176
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
```
```
In drivers/base/bus.c (ffffffff81ae8395)
Location: include/linux/device/bus.h:176
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/net/phy/phy_device.c (ffffffff81be3c8a)
Location: include/linux/device/bus.h:176
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819607c5)
Location: include/linux/device/bus.h:156
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
```
```
In drivers/base/bus.c (ffffffff81b36615)
Location: include/linux/device/bus.h:156
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3b75a)
Location: include/linux/device/bus.h:156
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819a9ee5)
Location: include/linux/device/bus.h:151
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
```
```
In drivers/base/bus.c (ffffffff81b8e035)
Location: include/linux/device/bus.h:151
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf0b5a)
Location: include/linux/device/bus.h:151
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8d44)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffff8000108f5174)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffff8000109404ec)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (ffff8000109d562c)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (ffff800010b9ee6c)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d7088)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (c09e14cc)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (c0a29bd8)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (c0abd138)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (c0c80bf8)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/vio.c (c0000000001012b4)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_find_node
```
```
In drivers/base/bus.c (c00000000097f748)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (c00000000098f5e4)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (c0000000009e930c)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (c000000000a964a0)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (c000000000c721f0)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057cf22)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffffffe000586440)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3ed4)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (ffffffe0006217e6)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (ffffffe000737172)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c37f5)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffffffff816ccf6c)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81702758)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (ffffffff817810e5)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (ffffffff818a268c)
Location: include/linux/device.h:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169eaa5)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffffffff816a829c)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816d6568)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (ffffffff81760e75)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (ffffffff8185ddfc)
Location: include/linux/device.h:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1cc5)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffffffff816fb4dc)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81737b78)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (ffffffff817b1495)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (ffffffff818f3c7c)
Location: include/linux/device.h:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170c505)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/devcon.c (ffffffff81715d7c)
Location: include/linux/device.h:186
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81752fb8)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
```
In drivers/net/phy/phy_device.c (ffffffff817cb425)
Location: include/linux/device.h:186
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_connect
```
```
In drivers/nvmem/core.c (ffffffff81914d1c)
Location: include/linux/device.h:186
Inline: True
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
</ul>

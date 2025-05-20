# Function: <code>of_platform_device_create</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_platform_device_create(struct device_node *np, const char *bus_id, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff8000114aa3a8)
Location: drivers/of/platform.c:210
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
Direct callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
  - drivers/video/fbdev/simplefb.c:simplefb_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
**Symbols:**

```
ffff800010b6d750-ffff800010b6d798: of_platform_device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_platform_device_create(struct device_node *np, const char *bus_id, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c15ae8c0)
Location: drivers/of/platform.c:210
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
```
**Symbols:**

```
c0c505d8-c0c505fc: of_platform_device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_platform_device_create(struct device_node *np, const char *bus_id, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c47fa0)
Location: drivers/of/platform.c:210
Inline: True
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_pdev_init
  - arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init
  - arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init
  - arch/powerpc/platforms/powernv/opal-sensor.c:opal_sensor_init
  - arch/powerpc/platforms/powernv/vas.c:vas_init
  - drivers/video/fbdev/simplefb.c:simplefb_init
  - drivers/misc/cxl/base.c:cxl_base_init
```
**Symbols:**

```
c000000000c47fa0-c000000000c47fbc: of_platform_device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_platform_device_create(struct device_node *np, const char *bus_id, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe00003a78a)
Location: drivers/of/platform.c:210
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_init
```
**Symbols:**

```
ffffffe000722372-ffffffe0007223ae: of_platform_device_create (STB_GLOBAL)
```
</details>
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

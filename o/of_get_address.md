# Function: <code>of_get_address</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
const __be32 *of_get_address(struct device_node *dev, int index, u64 *size, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b73080)
Location: drivers/of/address.c:715
Inline: False
Direct callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_show
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_show
  - drivers/of/address.c:of_address_to_resource
```
**Symbols:**

```
ffff800010b73080-ffff800010b73224: of_get_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const __be32 *of_get_address(struct device_node *dev, int index, u64 *size, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c54c84)
Location: drivers/of/address.c:715
Inline: False
Direct callers:
  - arch/arm/mach-exynos/exynos.c:exynos_sysram_init
  - arch/arm/mach-exynos/firmware.c:exynos_secure_firmware_available
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/of/address.c:of_address_to_resource
```
**Symbols:**

```
c0c54c84-c0c54e04: of_get_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const __be32 *of_get_address(struct device_node *dev, int index, u64 *size, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c4ee70)
Location: drivers/of/address.c:715
Inline: False
Direct callers:
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/video/fbdev/offb.c:offb_map_reg
  - drivers/of/address.c:of_address_to_resource
```
**Symbols:**

```
c000000000c4ee70-c000000000c4f090: of_get_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const __be32 *of_get_address(struct device_node *dev, int index, u64 *size, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe000726d72)
Location: drivers/of/address.c:715
Inline: False
Direct callers:
  - drivers/of/address.c:of_address_to_resource
```
**Symbols:**

```
ffffffe000726d72-ffffffe000726eba: of_get_address (STB_GLOBAL)
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

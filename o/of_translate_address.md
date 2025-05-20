# Function: <code>of_translate_address</code>

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
u64 of_translate_address(struct device_node *dev, const __be32 *in_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b73990)
Location: drivers/of/address.c:664
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/clk/mvebu/armada_ap_cp_helper.c:ap_cp_unique_name
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
```
**Symbols:**

```
ffff800010b73990-ffff800010b73a20: of_translate_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 of_translate_address(struct device_node *dev, const __be32 *in_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c55b50)
Location: drivers/of/address.c:664
Inline: False
Direct callers:
  - arch/arm/mach-exynos/exynos.c:exynos_sysram_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_parse_module_range
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/bus/ti-sysc.c:sysc_map_and_check_registers
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
```
**Symbols:**

```
c0c55b50-c0c55be0: of_translate_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 of_translate_address(struct device_node *dev, const __be32 *in_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c50320)
Location: drivers/of/address.c:664
Inline: False
Direct callers:
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_init_non_pci
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_map_reg
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
```
**Symbols:**

```
c000000000c50320-c000000000c503bc: of_translate_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 of_translate_address(struct device_node *dev, const __be32 *in_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe000727574)
Location: drivers/of/address.c:664
Inline: False
Direct callers:
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_pci_range_parser_one
  - drivers/of/address.c:of_pci_range_parser_one
```
**Symbols:**

```
ffffffe000727574-ffffffe0007275d8: of_translate_address (STB_GLOBAL)
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

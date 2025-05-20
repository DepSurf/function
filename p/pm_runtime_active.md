# Function: <code>pm_runtime_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8160a74e)
Location: include/linux/pm_runtime.h:91
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8166a2db)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8169800b)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ad16e)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a7b0b)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/usb/core/hub.c (ffffffff817188fe)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815df750)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172d4b7)
Location: include/linux/pm_runtime.h:85
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81757541)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81551843)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff815f9470)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8174fc57)
Location: include/linux/pm_runtime.h:85
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8177b97c)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815817a3)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8162b77e)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178ba37)
Location: include/linux/pm_runtime.h:84
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817b92dd)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a32a3)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8164d2ee)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817af657)
Location: include/linux/pm_runtime.h:84
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817e9b2d)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164be35)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff816fc0fe)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81875bf2)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/usb/core/hub.c (ffffffff818b9196)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670185)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff81718ffe)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818844d2)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/usb/core/hub.c (ffffffff818c7a76)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652685)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff816fa2fe)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81866d52)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/usb/core/hub.c (ffffffff818aaee6)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c43e1)
Location: include/linux/pm_runtime.h:141
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8177501a)
Location: include/linux/pm_runtime.h:141
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818f6152)
Location: include/linux/pm_runtime.h:141
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8193fe66)
Location: include/linux/pm_runtime.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea03b)
Location: include/linux/pm_runtime.h:171
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff818aad26)
Location: include/linux/pm_runtime.h:171
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81a46fa2)
Location: include/linux/pm_runtime.h:171
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/usb/core/hub.c (ffffffff81a97fac)
Location: include/linux/pm_runtime.h:171
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819100db)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff819f6316)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81bcdf62)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/usb/core/hub.c (ffffffff81c1adcc)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819537fb)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff81a3ea54)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abf38d)
Location: include/linux/pm_runtime.h:175
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81c25b52)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/usb/core/hub.c (ffffffff81c81cfc)
Location: include/linux/pm_runtime.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cc8b)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff81a8a384)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b121c2)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81cd82d2)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/usb/core/hub.c (ffffffff81d3663c)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bd50)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffff8000107bf800)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/usb/core/hub.c (ffff800010a19384)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/bus/ti-sysc.c (c0827b4c)
Location: include/linux/pm_runtime.h:84
Inline: True
```
```
In drivers/gpio/gpio-omap.c (c086d1e0)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
```
```
In drivers/clk/clk.c (c08e81a4)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/iommu/exynos-iommu.c (c09ca104)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
```
```
In drivers/usb/core/hub.c (c0af1550)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
```
In drivers/usb/musb/musb_core.c (c0b64c04)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_queue_resume_work
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad27a4)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8712)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffe00050b0fc)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/usb/core/hub.c (ffffffe00063df18)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596ab3)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8161334e)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81774187)
Location: include/linux/pm_runtime.h:84
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817a1f0d)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81585c43)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8160787e)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81753f37)
Location: include/linux/pm_runtime.h:84
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81793d4d)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596ff3)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8164112e)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817a44d7)
Location: include/linux/pm_runtime.h:84
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817de9ad)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1433)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8165b4ae)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817be357)
Location: include/linux/pm_runtime.h:84
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817f8c9d)
Location: include/linux/pm_runtime.h:84
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
</ul>

## Differences

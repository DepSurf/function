# Function: <code>bus_register_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8154a5c0)
Location: drivers/base/bus.c:987
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff8154a5c0-ffffffff8154a5de: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159c1f0)
Location: drivers/base/bus.c:986
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff8159c1f0-ffffffff8159c20e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815ca750)
Location: drivers/base/bus.c:986
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff815ca750-ffffffff815ca76e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815df420)
Location: drivers/base/bus.c:945
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/silead_dmi.c:silead_ts_dmi_init
```
**Symbols:**

```
ffffffff815df420-ffffffff815df43e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81646450)
Location: drivers/base/bus.c:945
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/silead_dmi.c:silead_ts_dmi_init
```
**Symbols:**

```
ffffffff81646450-ffffffff8164646e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81681930)
Location: drivers/base/bus.c:943
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/silead_dmi.c:silead_ts_dmi_init
```
**Symbols:**

```
ffffffff81681930-ffffffff8168194e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a13d0)
Location: drivers/base/bus.c:950
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff816a13d0-ffffffff816a13ee: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816da1a0)
Location: drivers/base/bus.c:924
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff816da1a0-ffffffff816da1be: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fe150)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff816fe150-ffffffff816fe16e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b74a0)
Location: drivers/base/bus.c:901
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff817b74a0-ffffffff817b74be: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cc1c0)
Location: drivers/base/bus.c:901
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_driver_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff817cc1c0-ffffffff817cc1de: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817afb30)
Location: drivers/base/bus.c:884
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff817afb30-ffffffff817afb4e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81838cb0)
Location: drivers/base/bus.c:880
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff81838cb0-ffffffff81838cce: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197b1d0)
Location: drivers/base/bus.c:882
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff8197b1d0-ffffffff8197b1f6: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae8200)
Location: drivers/base/bus.c:882
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff81ae8200-ffffffff81ae8226: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bus_register_notifier(const struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36a00)
Location: drivers/base/bus.c:953
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff81b36a00-ffffffff81b36a4f: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bus_register_notifier(const struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8e420)
Location: drivers/base/bus.c:953
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/intel/dmar.c:dmar_register_bus_notifier
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff81b8e420-ffffffff81b8e46f: bus_register_notifier (STB_GLOBAL)
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
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e90e0)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - drivers/xen/arm-device.c:register_xen_amba_notifier
  - drivers/xen/arm-device.c:register_xen_platform_notifier
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffff8000108e90e0-ffff8000108e9118: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d7408)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - arch/arm/mach-highbank/highbank.c:highbank_init
  - arch/arm/mach-highbank/highbank.c:highbank_init
  - arch/arm/mach-mvebu/coherency.c:coherency_pci_init
  - arch/arm/mach-mvebu/coherency.c:coherency_late_init
  - arch/arm/mach-omap2/omap_device.c:__omap_device_init
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - drivers/bus/ti-sysc.c:sysc_init
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
c09d7408-c09d742c: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097f910)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_init
  - arch/powerpc/platforms/powernv/pci.c:__machine_initcall_powernv_pnv_tce_iommu_bus_notifier_init
  - arch/powerpc/platforms/pseries/iommu.c:__machine_initcall_pseries_tce_iommu_bus_notifier_init
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
c00000000097f910-c00000000097f94c: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057d070)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffe00057d070-ffffffe00057d0a8: bus_register_notifier (STB_GLOBAL)
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
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c3940)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
```
**Symbols:**

```
ffffffff816c3940-ffffffff816c395e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169ebf0)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
```
**Symbols:**

```
ffffffff8169ebf0-ffffffff8169ec0e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1e10)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff816f1e10-ffffffff816f1e2e: bus_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bus_register_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170c650)
Location: drivers/base/bus.c:900
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/xen/pci.c:register_xen_pci_notifier
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_register_bus_notifier
  - drivers/base/power/clock_ops.c:pm_clk_add_notifier
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/platform/x86/touchscreen_dmi.c:ts_dmi_init
```
**Symbols:**

```
ffffffff8170c650-ffffffff8170c66e: bus_register_notifier (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type *bus</code> ➡️ <code>const struct bus_type *bus</code>
</li>
</ul>
</details>
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

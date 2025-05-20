# Function: <code>__request_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086ab0)
Location: kernel/resource.c:1061
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81086ab0-ffffffff81086c4a: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089b00)
Location: kernel/resource.c:1127
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81089b00-ffffffff81089c8d: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ea50)
Location: kernel/resource.c:1127
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8108ea50-ffffffff8108ebde: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ba10)
Location: kernel/resource.c:1127
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff8108ba10-ffffffff8108bb9d: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092790)
Location: kernel/resource.c:1145
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff81092790-ffffffff81092920: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096150)
Location: kernel/resource.c:1115
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff81096150-ffffffff810962dd: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e4c0)
Location: kernel/resource.c:1109
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff8109e4c0-ffffffff8109e64d: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810a3977-ffffffff810a3992: __request_region.cold (STB_LOCAL)
ffffffff810a2a60-ffffffff810a2bf2: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810a9f6b-ffffffff810a9f86: __request_region.cold (STB_LOCAL)
ffffffff810a9030-ffffffff810a91c2: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:alloc_memory_target
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810b1b16-ffffffff810b1b31: __request_region.cold (STB_LOCAL)
ffffffff810b0520-ffffffff810b06ba: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1130
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:alloc_memory_target
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff81bdb7ff-ffffffff81bdb81a: __request_region.cold (STB_LOCAL)
ffffffff810abc40-ffffffff810abdda: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad310)
Location: kernel/resource.c:1222
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810ad310-ffffffff810ad396: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bee80)
Location: kernel/resource.c:1222
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810bee80-ffffffff810bef06: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5dc0)
Location: kernel/resource.c:1209
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810d5dc0-ffffffff810d5e72: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f50e0)
Location: kernel/resource.c:1217
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810f50e0-ffffffff810f5192: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101520)
Location: kernel/resource.c:1217
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff81101520-ffffffff811015d2: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110ac40)
Location: kernel/resource.c:1272
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:register_memory_resource
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff8110ac40-ffffffff8110ad21: __request_region (STB_GLOBAL)
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
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100ce8)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_reserve_range
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/amba/bus.c:amba_request_regions
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/amba-pl011.c:pl011_request_port
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
ffff800010100ce8-ffff800010100f2c: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d088)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init
  - kernel/resource.c:__devm_request_region
  - fs/pstore/ram_core.c:persistent_ram_new
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_request_ctx
  - drivers/amba/bus.c:amba_request_regions
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/amba-pl011.c:pl011_request_port
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/mfd/sm501.c:sm501_pci_probe
  - drivers/mfd/sm501.c:sm501_plat_probe
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
c035d088-c035d274: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000148240)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
  - arch/powerpc/platforms/powernv/vas-window.c:map_mmio_region
  - arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup
  - arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup
  - arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup
  - arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup
  - arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup
  - arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
c000000000148240-c000000000148490: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c80da)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
ffffffe0000c80da-ffffffe0000c8264: __request_region (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810a388b-ffffffff810a38a6: __request_region.cold (STB_LOCAL)
ffffffff810a2950-ffffffff810a2ae2: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/hv/vmbus_drv.c:vmbus_acpi_add
  - drivers/hv/vmbus_drv.c:vmbus_allocate_mmio
  - drivers/hv/vmbus_drv.c:vmbus_allocate_mmio
  - drivers/hv/vmbus_drv.c:vmbus_allocate_mmio
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff8109226b-ffffffff81092286: __request_region.cold (STB_LOCAL)
ffffffff81091330-ffffffff810914c2: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810a383b-ffffffff810a3856: __request_region.cold (STB_LOCAL)
ffffffff810a2900-ffffffff810a2a92: __request_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct resource *__request_region(struct resource *parent, resource_size_t start, resource_size_t n, const char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1123
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/quirks.c:quirk_ati_exploding_mce
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/osl.c:acpi_request_region
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/system.c:reserve_range
  - drivers/pnp/system.c:reserve_range
  - drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff
```
**Symbols:**

```
ffffffff810ab8f9-ffffffff810ab914: __request_region.cold (STB_LOCAL)
ffffffff810aa980-ffffffff810aab1c: __request_region (STB_GLOBAL)
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

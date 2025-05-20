# Function: <code>__release_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086850)
Location: kernel/resource.c:1118
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81086850-ffffffff8108690e: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810898a0)
Location: kernel/resource.c:1186
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810898a0-ffffffff8108995e: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e7f0)
Location: kernel/resource.c:1186
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8108e7f0-ffffffff8108e8ae: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b7e0)
Location: kernel/resource.c:1186
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8108b7e0-ffffffff8108b897: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092560)
Location: kernel/resource.c:1204
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81092560-ffffffff81092617: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095f50)
Location: kernel/resource.c:1174
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81095f50-ffffffff81096009: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e2c0)
Location: kernel/resource.c:1168
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8109e2c0-ffffffff8109e379: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2830)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810a2830-ffffffff810a28fb: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8e00)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810a8e00-ffffffff810a8ecb: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0230)
Location: kernel/resource.c:1196
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/numa/hmat.c:hmat_free_structures
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810b0230-ffffffff810b02fb: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab950)
Location: kernel/resource.c:1203
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/numa/hmat.c:hmat_free_structures
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810ab950-ffffffff810aba1b: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810accd0)
Location: kernel/resource.c:1256
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810accd0-ffffffff810acd9b: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810be840)
Location: kernel/resource.c:1256
Inline: False
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810be840-ffffffff810be90b: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5f40)
Location: kernel/resource.c:1243
Inline: False
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810d5f40-ffffffff810d601b: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f5280)
Location: kernel/resource.c:1251
Inline: False
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810f5280-ffffffff810f538f: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811016c0)
Location: kernel/resource.c:1251
Inline: False
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff811016c0-ffffffff811017cf: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110ae10)
Location: kernel/resource.c:1306
Inline: False
Direct callers:
  - kernel/resource.c:__devm_release_region
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/apei-base.c:apei_resources_request
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:trim_dev_dax_range
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8110ae10-ffffffff8110af1f: __release_region (STB_GLOBAL)
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
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100ac0)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/amba/bus.c:amba_release_regions
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
  - drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_exit_key
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/amba-pl011.c:pl011_release_port
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/tty/serial/msm_serial.c:msm_release_port
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_release_attrib
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
ffff800010100ac0-ffff800010100c0c: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035ccdc)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init
  - kernel/resource.c:devm_region_release
  - fs/pstore/ram_core.c:persistent_ram_free
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/amba/bus.c:amba_release_regions
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/amba-pl011.c:pl011_release_port
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/tty/serial/msm_serial.c:msm_release_port
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_remove
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_remove
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
c035ccdc-c035cdfc: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147da0)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:unmap_winctx_mmio_bars
  - arch/powerpc/platforms/powernv/vas-window.c:unmap_winctx_mmio_bars
  - kernel/resource.c:__devm_release_region
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/gxt4500.c:gxt4500_remove
  - drivers/video/fbdev/gxt4500.c:gxt4500_remove
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_destroy
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
c000000000147da0-c000000000147f30: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c82fe)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_put
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/of/address.c:of_io_request_and_map
```
**Symbols:**

```
ffffffe0000c82fe-ffffffe0000c83d6: __release_region (STB_GLOBAL)
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
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2720)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810a2720-ffffffff810a27eb: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091100)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/hv/vmbus_drv.c:vmbus_free_mmio
  - drivers/hv/vmbus_drv.c:vmbus_free_mmio
  - drivers/hv/vmbus_drv.c:vmbus_allocate_mmio
  - drivers/hv/vmbus_drv.c:vmbus_acpi_remove
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81091100-ffffffff810911cb: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a26d0)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810a26d0-ffffffff810a279b: __release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __release_region(struct resource *parent, resource_size_t start, resource_size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa700)
Location: kernel/resource.c:1191
Inline: False
Direct callers:
  - kernel/resource.c:devm_region_release
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_destroy
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/apei-base.c:apei_resources_release
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:nvdimm_map_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff810aa700-ffffffff810aa7d5: __release_region (STB_GLOBAL)
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

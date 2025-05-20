# Function: <code>_dev_notice</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169dab0)
Location: drivers/base/core.c:3097
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff8169dab0-ffffffff8169db33: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d9026)
Location: drivers/base/core.c:3351
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff816d9026-ffffffff816d90a9: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fd0ac)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff816fd0ac-ffffffff816fd12f: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b69ff)
Location: drivers/base/core.c:3971
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff817b69ff-ffffffff817b6a82: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c0e164)
Location: drivers/base/core.c:4369
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff81c0e164-ffffffff81c0e1e7: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c00502)
Location: drivers/base/core.c:4596
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff81c00502-ffffffff81c00585: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81d02a73)
Location: drivers/base/core.c:4661
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff81d02a73-ffffffff81d02af6: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ecb15a)
Location: drivers/base/core.c:4695
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff81ecb15a-ffffffff81ecb201: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae3190)
Location: drivers/base/core.c:4914
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ssp_isoc_endpoint_companion
```
**Symbols:**

```
ffffffff81ae3190-ffffffff81ae3230: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b311c0)
Location: drivers/base/core.c:4919
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ssp_isoc_endpoint_companion
```
**Symbols:**

```
ffffffff81b311c0-ffffffff81b31260: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b887c0)
Location: drivers/base/core.c:4932
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_interface
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ssp_isoc_endpoint_companion
```
**Symbols:**

```
ffffffff81b887c0-ffffffff81b88860: _dev_notice (STB_GLOBAL)
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
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e7d44)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu-impl.c:cavium_cfg_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffff8000108e7d44-ffff8000108e7dd8: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d6110)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
c09d6110-c09d6190: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097dfe8)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
c00000000097dfe8-c00000000097e08c: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057c166)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffe00057c166-ffffffe00057c1c2: _dev_notice (STB_GLOBAL)
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
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c289c)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff816c289c-ffffffff816c291f: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169db4c)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff8169db4c-ffffffff8169dbcf: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f0d6c)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff816f0d6c-ffffffff816f0def: _dev_notice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _dev_notice(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170b5ac)
Location: drivers/base/core.c:3503
Inline: False
Direct callers:
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/usb/core/hub.c:usb_root_hub_lost_power
```
**Symbols:**

```
ffffffff8170b5ac-ffffffff8170b62f: _dev_notice (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

# Function: <code>devm_kfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815501c0)
Location: drivers/base/devres.c:883
Inline: True
Direct callers:
  - drivers/base/component.c:component_match_realloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff815501c0-ffffffff81550201: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1fc0)
Location: drivers/base/devres.c:883
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff815a1fc0-ffffffff815a2001: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815d06e0)
Location: drivers/base/devres.c:884
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff815d06e0-ffffffff815d0721: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4e70)
Location: drivers/base/devres.c:884
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff815e4e70-ffffffff815e4ea2: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164c150)
Location: drivers/base/devres.c:884
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff8164c150-ffffffff8164c182: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687760)
Location: drivers/base/devres.c:888
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81687760-ffffffff81687789: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a76d0)
Location: drivers/base/devres.c:918
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff816a76d0-ffffffff816a770c: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/devres.c (ffffffff816e099d)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff816e099d-ffffffff816e09b0: devm_kfree.cold (STB_LOCAL)
ffffffff816e0840-ffffffff816e0885: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704a00)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81704a00-ffffffff81704a45: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817bf090)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:set_freq_table
```
**Symbols:**

```
ffffffff817bf090-ffffffff817bf153: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3df0)
Location: drivers/base/devres.c:1056
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:set_freq_table
```
**Symbols:**

```
ffffffff817d3df0-ffffffff817d3eb9: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b7800)
Location: drivers/base/devres.c:1056
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff817b7800-ffffffff817b78c9: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840fb0)
Location: drivers/base/devres.c:1045
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81840fb0-ffffffff81841008: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81984340)
Location: drivers/base/devres.c:1045
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81984340-ffffffff819843c1: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af2480)
Location: drivers/base/devres.c:1050
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81af2480-ffffffff81af2501: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b40630)
Location: drivers/base/devres.c:1051
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b40630-ffffffff81b406b1: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b984d0)
Location: drivers/base/devres.c:1051
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/gpu/drm/bridge/panel.c:drmm_drm_panel_bridge_release
  - drivers/gpu/drm/bridge/panel.c:devm_drm_panel_bridge_release
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_put_battery_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b984d0-ffffffff81b98551: devm_kfree (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f07c0)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/bus/fsl-mc/mc-io.c:fsl_destroy_mc_io
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_cleanup_all_resource_pools
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_port_free
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/iommu/arm-smmu-impl.c:arm_smmu_impl_init
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
```
**Symbols:**

```
ffff8000108f07c0-ffff8000108f0834: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09ddc28)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_free
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_port_free
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/iommu/tegra-smmu.c:tegra_smmu_device_group
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_destroy
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_create
  - drivers/usb/musb/musb_core.c:musb_queue_resume_work
  - drivers/usb/musb/musb_core.c:musb_run_resume_work
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_free_mrq
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/memory/of_memory.c:of_get_ddr_timings
  - drivers/memory/of_memory.c:of_get_min_tck
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_dai
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_dai
```
**Symbols:**

```
c09ddc28-c09ddc9c: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989c10)
Location: drivers/base/devres.c:940
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
c000000000989c10-c000000000989c84: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582da6)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/pinctrl/core.c:pinctrl_generic_remove_group
  - drivers/pinctrl/pinmux.c:pinmux_generic_remove_function
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffe000582da6-ffffffe000582e0e: devm_kfree (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816ca150)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff816ca150-ffffffff816ca195: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a5480)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff816a5480-ffffffff816a54c5: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f86c0)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff816f86c0-ffffffff816f8705: devm_kfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_kfree(struct device *dev, const void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712f60)
Location: drivers/base/devres.c:940
Inline: True
Direct callers:
  - block/badblocks.c:badblocks_exit
  - drivers/virtio/virtio_mmio.c:virtio_mmio_release_dev
  - drivers/base/regmap/regmap.c:devm_regmap_field_free
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81712f60-ffffffff81712fa5: devm_kfree (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *p</code> ➡️ <code>const void *p</code>
</li>
</ul>
</details>
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

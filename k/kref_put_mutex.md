# Function: <code>kref_put_mutex</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3d4b)
Location: include/linux/kref.h:76
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/net/phy/sfp-bus.c (ffffffff8173adb5)
Location: include/linux/kref.h:76
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/opp/core.c (ffffffff8181cb25)
Location: include/linux/kref.h:76
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/net/phy/sfp-bus.c (ffffffff8175e605)
Location: include/linux/kref.h:73
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/opp/core.c (ffffffff818486e5)
Location: include/linux/kref.h:73
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (ffffffff8179bc75)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/opp/core.c (ffffffff8188b755)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (ffffffff817bf725)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/vfio/vfio.c (ffffffff817d0571)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7499)
Location: include/linux/kref.h:71
Inline: True
```
```
In drivers/opp/core.c (ffffffff818bd825)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81888d58)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
```
In drivers/vfio/vfio.c (ffffffff8189c353)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a4dc7)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/opp/core.c (ffffffff81991111)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
```
**Symbols:**

```
ffffffff8198df40-ffffffff8198df66: kref_put_mutex.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81897018)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
```
In drivers/vfio/vfio.c (ffffffff818aaf63)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b3e97)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/opp/core.c (ffffffff81992d06)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_bw
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
```
**Symbols:**

```
ffffffff819919b0-ffffffff819919d6: kref_put_mutex.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int kref_put_mutex(struct kref *kref, void (*release)(struct kref *), struct mutex *lock);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81879908)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
```
In drivers/vfio/vfio.c (ffffffff8188e6a3)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897034)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/opp/core.c (ffffffff81976e72)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
```
**Symbols:**

```
ffffffff81975dc0-ffffffff81975df1: kref_put_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int kref_put_mutex(struct kref *kref, void (*release)(struct kref *), struct mutex *lock);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8190a768)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
```
In drivers/vfio/vfio.c (ffffffff81921ce3)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
```
In drivers/opp/core.c (ffffffff81a1fc60)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
```
**Symbols:**

```
ffffffff81a1e950-ffffffff81a1e981: kref_put_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5def3)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
```
In drivers/opp/core.c (ffffffff81b887f1)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
```
**Symbols:**

```
ffffffff81b87700-ffffffff81b87733: kref_put_mutex.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81be8b93)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
```
In drivers/opp/core.c (ffffffff81d28541)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff81d27220-ffffffff81d27253: kref_put_mutex.isra.0 (STB_LOCAL)
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
In drivers/net/phy/sfp-bus.c (ffffffff81c40fc3)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
```
In drivers/opp/core.c (ffffffff81d916de)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
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
In drivers/net/phy/sfp-bus.c (ffffffff81cf6633)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
```
In drivers/opp/core.c (ffffffff81e49350)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add_dynamic
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
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
In drivers/net/phy/sfp-bus.c (ffff8000109d9bc0)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/opp/core.c (ffff800010b185c8)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (c0ac07c4)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/opp/core.c (c0bf3564)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (c000000000a9b6e4)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/vfio/vfio.c (c000000000aae658)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab68ac)
Location: include/linux/kref.h:71
Inline: True
```
```
In drivers/opp/core.c (c000000000c09c60)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (ffffffe000624a9e)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/opp/core.c (ffffffe00070118c)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (ffffffff817841f5)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/opp/core.c (ffffffff81861f45)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (ffffffff81763b45)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/vfio/vfio.c (ffffffff8177a621)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781549)
Location: include/linux/kref.h:71
Inline: True
```
```
In drivers/opp/core.c (ffffffff8182abf5)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (ffffffff817b45a5)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/vfio/vfio.c (ffffffff817c53f1)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc319)
Location: include/linux/kref.h:71
Inline: True
```
```
In drivers/opp/core.c (ffffffff818b2cd5)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
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
In drivers/net/phy/sfp-bus.c (ffffffff817ce575)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
```
```
In drivers/vfio/vfio.c (ffffffff817df691)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e65b9)
Location: include/linux/kref.h:71
Inline: True
```
```
In drivers/opp/core.c (ffffffff818cef85)
Location: include/linux/kref.h:71
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>

# Function: <code>refcount_dec_and_mutex_lock</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8146c570)
Location: lib/refcount.c:306
Inline: True
```
**Symbols:**

```
ffffffff8146c570-ffffffff8146c5b8: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81498890)
Location: lib/refcount.c:307
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff81498890-ffffffff814988de: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814cdae0)
Location: lib/refcount.c:307
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff814cdae0-ffffffff814cdb26: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e23b0)
Location: lib/refcount.c:306
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffffffff814e23b0-ffffffff814e23f6: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150e260)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffffffff8150e260-ffffffff8150e2b8: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152c0b0)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffffffff8152c0b0-ffffffff8152c108: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8158f8b0)
Location: lib/refcount.c:113
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
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
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
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
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff8158f8b0-ffffffff8158f932: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815ac3e0)
Location: lib/refcount.c:113
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
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
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
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
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff815ac3e0-ffffffff815ac462: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815b70b0)
Location: lib/refcount.c:113
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
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
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
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
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff815b70b0-ffffffff815b7132: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/refcount.c (ffffffff8161d70b)
Location: lib/refcount.c:113
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
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
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81cdade2-ffffffff81cdadf6: refcount_dec_and_mutex_lock.cold (STB_LOCAL)
ffffffff8161d6e0-ffffffff8161d76e: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:113
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:__vfio_register_dev
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
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff81e9369e-ffffffff81e936b2: refcount_dec_and_mutex_lock.cold (STB_LOCAL)
ffffffff816eb1e0-ffffffff816eb268: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:113
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
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
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff82078866-ffffffff8207887a: refcount_dec_and_mutex_lock.cold (STB_LOCAL)
ffffffff817db870-ffffffff817db8f8: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:113
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
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
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff820f8e11-ffffffff820f8e25: refcount_dec_and_mutex_lock.cold (STB_LOCAL)
ffffffff8181aae0-ffffffff8181ab68: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:113
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_leave
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
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
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffff821d6932-ffffffff821d6946: refcount_dec_and_mutex_lock.cold (STB_LOCAL)
ffffffff8185fe60-ffffffff8185fee8: refcount_dec_and_mutex_lock (STB_GLOBAL)
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
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637a60)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffff800010637a60-ffff800010637abc: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd910)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
c07dd910-c07dd964: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007ddf30)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
c0000000007ddf30-c0000000007de000: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464e00)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
  - net/sched/act_api.c:__tcf_action_put
```
**Symbols:**

```
ffffffe000464e00-ffffffe000464e74: refcount_dec_and_mutex_lock (STB_GLOBAL)
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
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81524690)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffffffff81524690-ffffffff815246e8: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81514970)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffffffff81514970-ffffffff815149c8: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81520720)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffffffff81520720-ffffffff81520778: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_mutex_lock(refcount_t *r, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8153a0a0)
Location: lib/refcount.c:314
Inline: True
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_put
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/opp/core.c:_put_opp_list_kref
  - net/core/rtnetlink.c:refcount_dec_and_rtnl_lock
```
**Symbols:**

```
ffffffff8153a0a0-ffffffff8153a0f8: refcount_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
